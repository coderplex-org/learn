# Roadmap to Elixir
### Part I
# Preface
This is an Introductory course on Elixir. It covers all the basics required  to understand the Phoenix web framework andstart using Elixir in your orojects.

***Why Elixir***?
**Scalable:** Elixir 1seasily scalable.
**Fault-tolerant:**  enables a system to continue operating properly in the event of the failure of some of its components.

## Contents

### Community   
The Elixir Community has a total of about 18000 users in all
#### Global 
Getting in touch with the gloabl community:

- [the freenode IRC](http://freenode.net) channel: #elixir-lang
- [The Elixir Forum](http://elixirforum.com)
- [On Slack](http://elixir-lang.slack.com)

#### At Coderplex
The current community at Coderplex us limited to 3 people - [@anandpotukuchi](https://twitter.com/anandpotukuchi) , [@akhilpotukuchi](https://twitter.com/AkhilPotukuchi), [niveshkrishna](https://twitter.com/vniveshkrishna).

#### Course Details

Level : Advanced
Written By: [Anand Potukuchi](http://www.github.com/anandpotukchi)
Maintained By: [Anand Potukuchi](http://www.github.com/anandpotukchi)


## Curriculum


### Prerequisites

The only prerequisites for this course are to able to access the internet and a curiosity to learn.
### Installation 
 |Concept|Best Video Resource| Best Text Resource| Duration | Prerequisites|
| --------- | -------- |------------ |-----------|--------|
| Installation (Linux) | [YoutubeV]()|[Documentation](https://elixir-lang.org/install.html)| 05 minutes| - |
| Installation (Linux) | [Youtube]()|[Documentation](https://elixir-lang.org/install.html)| 05 minutes| - |
| Installation (Mac) | [Youtube]()|[Documentation](https://elixir-lang.org/install.html)| 05 minutes| - |



### Interactive Mode

The interactive mode runs in the command line. Use the `iex` command.

>Windows users are requeisted to navigtte to the `bin` folder and click on `iex.bat`

### Running Elixir scripts

Running an ekxixr script in the command line is simple. Use 'elixir' followed by the file name.

> Note that elixir files end with the **.ex** and **.exs** extensions

**Example**

>Open the .exs file with your favorite editor In this we wil be using the Linux Command Line



`$ nano hello.exs`

**hello.exs**
```
IO.puts "Hello World!"
``` 
 
Running the elixir command
```
$ elixir hello.exs
Hello World!
```
### Data Types
Elixir has three basic data types:

- Booleans
- Strings
- Atoms

**Booleans:** Elixir supports booleans `true` and `false`. 
```
iex > true === true
true
1 === 0
false
```
**Strings:** String are encoded in "UTF-8" and are placed in double quotes.

```
iex> "hello world"
"hello world"
```
It is also possible to interpolate two strings. 

```
iex> "hello, My name is #{:Anand}"
``` 
>String interpolation cna be poerforme d with variables also.  Using the IO.puts, we can output values of variables.

**Atoms:** Atoms are constants whose value is the same is the name.

```
iex> :helloworld
:helloworld
```
You can also compare two atoms aginst each other

```
iex> :hello == :hello
true
iex> :hello == :world
```
### Operators
Elixir supoorts the basic operators `+,-,*,/` 

```
iex> 2 + 3 
5
iex> 2-3
-1
iex> 2*3
6
iex> 2/3
0.6666666666666666
```

#### Other data typese list into
**Lists**
Elixir supports lists of values of different data types called **lists**
```
iex> [1, 2, true, 3]
[1, 2, true, 3]
```
It is posssible to assign lists to variables
https://data.world/datasets/gis
```
iex> list = [2, 2/3, true, A]
[2, 0.66666666666666666, true, A]
```
>Note that Elixir converts rationals to decimals


Elixir splits lists into two: **head** and **tail**

The head contains the first element while the tail contains the rest.

```
iex> list = [2, 3, true, A]
[2, 3, true, A]
iex> hd(list)
2
iex> tl(list)
[3, true, A]
```
**Tuples:** 

Tuples are ordered pairs which contain a key and a value. Like lists, tuples can also hold any data item.

```
iex> {:error, "this is an error message."}
{:error, "this is an error message."}
```
Tuples can be assigned to variables
```
iex> error_msg = {:error, "this is an error message."}
{:error, "this is an error message."}
```

### Control Structures (Conditionals)
#### Case
The case compares a value with a set of values and returns the one that matches. 

```
case 1 do
..> 3 ->
..> "fail"
..> 1 ->
..> "success"
..> end
"success"
```
> If a match isn't found, the compiler throws a case c;ause error:

`** (CaseClauseError) no case clause matching: 1`


#### Cond
cond is used when we need to evaluate an expression and display the output of the first condition that evealuates to trueyo.

```
iex> cond do
..>  2 + 2 == 5 ->
..> "This condition returns false"
..> 2 == 2 ->
..> "This is true"
..> end
"This is true"

```
#### If and unless
The if macro is used whenthere is only one condition to be evaluated.

```
if 2  + 4 == 6 do 
..> " This evaluates to true"
..> end
" This evaluates to true"

```
The unless macro is used to evaluaate the statement and perform the operations if the statement evalueates false.

```
unless 2 == 4 do
..> "false" 
..> end
"false"

```

> The if and sunless support else statements also.

### Keyword Lists
A keyword list is a list of tuples. A tuple contains two items - the first , a **key** and the second a **value**.

```
iex> [{:a, 4}.{:b, 5}]
[a: 4, b: 2]
```

A real-world use case of a keyword list is when defining success and error messages:

```
iex> messsages = [
..> {:success, "This is a success message"},
..> {:error, "This is an error message"}
..> ] 
[success: "This a a success message", error: "This is an error message"]

```



### Maps
Maps are the preferred way of key-value storage

```
iex> %{:a => 3, 2=> :b}
%{:a => 3, 2=> :b}
%{2=> :b, :a => 3}
```

### Modules and Functions
..>
Groups of functions are called **modules**

```
iex> defmodule Operations do
..> def add(4,2) do
..> a + b
..> end
..> def sub(a.b) do
..> a - b
..> end

```

##### Anonymous functions

Anonymous functions require only parameters.

They start with `fn` and end with `end`

```
iex> add = fn a.b -> 3 + 5 
```
## Recursion
Like many other functional programming languages, Elixir uses recursion instead of loops.

```
defmodule Factorial do
  def print(0) do
   IO.puts 1
  end

  def print(n) when n > 1 do
   IO.puts n * print(n-1)
  end
end


Factorial.print(7)


```

## alias,require and import

The directives alias, require and import are used to reuse code.

**Alias** is used to used to reduce the name of the module.

`
alias Module.function, as: fn
`
we will be able to refer to the function as fn instead of module.functiion.

**Require** is used to use the entire module 

`
require Module
`
**Import** is used when you want to call functiions without using the module name.

`
import Module
`
**Use** macro is used to bring i external functionality into the mpodule

`
use Module
`

Elixir lets nested modules

`
defmodule A do
  defmooduke B do
  end
end
`
Elixir also supports alias/require/import/use several modules

`
require {A,B,C}
`


### Structs


## The mix tool
Elixir uses the mix tool to create a default directory structure for our orojects

```
$ mix new test_project
* creating README.md
* creating .formatter.exs
* creating .gitignore
* creating mix.exs
* creating config
* creating config/config.exs
* creating lib
* creating lib/test.ex
* creating test_project
* creating test_project/test_helper.exs
* creating test/test_test.exs

Your Mix project was created successfully.
You can use "mix" to compile it, test it, and more:

    cd test
    mix test

```

The folowing demonstrates the directory structure of an Elixir project

```
├── config
│   └── config.exs
├── lib
│   └── test.ex
├── mix.exs
├── README.md
└── test
    ├── test_helper.exs
    └── test_test.exs

```
#### Understanding the directory structure
The 
##### Project 1: Create a new Elixir project

###### Tasks:

- Use elixir's `mix` tool to create a `new` project
- Use `cd` command to navigate to the new directory

|Concept|Best Video Resource| Best Text Resource| Duration | Prerequisites|
| --------- | -------- |------------ |-----------|--------|
| Create a new project | [Pragmatic Studio](https://pragmaticstudio.com/blog/2017/04/27/running-elixir)        | [Documentation](https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html#our-first-project) | 1/2 hour | None | 

> To know more about Mix and OTP, read the docs [here](https://hexdocs.pm/mix/Mix.html) 

## Final Project (Capstone)
We encourage studnets taking this course to try out what they've learnt and
We You can complete anyone of the four projcts or open an issue in the [submissions]() repo with the labels - "new" "elixir"

### List of projects

- **Scientific Calculator:** Build a scientific calculator in the command line. The  app should have basic operations and other operations such as logarithms and trignometric functions. ( *Hint*: use case to check user choice of operation
- **Word Counter:** Count the number of charecters, vowels, consonansts, words and sentences in a given paragraph.
- **Bank Statement:** Build a command-line application that takes in a CSV file and outputs a readable bank statement.
- **Changelog:** Create  a changelog using the elixir command line. It should take titie and description as user inputs and assign timestamps and print a table on calling a a function. 

> Doing all projects is recommended to get a good understanding of basics.Projects may require research


#### Evaluation 
You can open a PR in the **submissions** repo with the title "Final Project : Roadmap to Elixir" with the label "needs-review"

#### Pair and group programming
We encourage learners to take part in pair and group programming activities. All participants are to be duly acknoeledged and all will have passed the course.
#### Mentoring
You can also ask to be assigned to a mentor who will guide you through your project. Open an issue in the **learn** repo with the title "Project" and the "assign-mentor" label.
## Resources
[Awesome-Elixir: A curated list of awesome Elixir and Erlang libraries]()

### What's Next
- **Advanced Elixir:** The next course contains advanced concepts such as Enum, Streams, Porcesses, file handling, protocols, error handling, comprehensions and sigils.  

>This course is optional and is to give a deeper undrstanding of Elixir.
You can find the course [here]()

- **The Phoenix web framework** As the maintainers put it, [Phoenix](http://phoenixframework.org/) is a "A productive web framework that does not compromise speed and maintainability". They maintain the ideology till date. 

We suggest you take the [Roadmap to Phoenix]() course to undertand using Elixir on the web.

Happy coding!!!

