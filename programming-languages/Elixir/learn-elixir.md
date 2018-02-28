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

### Conditionals
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

#### If and unless

### Keyword Lists

### Maps

### Modules and Functions

##### Modules
##### Functions
##### Anonymous functions
Anonymous functions do not require a name

They start with `fn` and end with `end`

```
iex> add = fn a.b -> 3 + 5 
```
## Recursion



### alias,require and import

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
## Final Project (Capstone)
We encourage studnets taking this course to try out what they've learnt and
We You can complete anyone of the four projcts or open an issue in the [submissions]() repo with the labels - "new" "elixir"

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

