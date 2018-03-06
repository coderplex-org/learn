# Roadmap to Elixir
### Part II
# Preface
This course is an advanced course on the Elixir programming language. It's designed for one with a  a basic understanding of the language and want to know more of the language's many hidden goodies. 
## Course Details
**Level:** Advanced 
Written By: [Anand Potukuchi](http://www.github.com/anandpotukchi)
Maintained By: [Anand Potukuchi](http://www.github.com/anandpotukchi)
### Contents

## Curriculum

### Prerequisites
This course assumes that you have command over basic Elixir syntax or have taken the Roadmap to [Elixir Part I]()

## Enum and Streams
Enumerables are datab types w1hich map a value to a key. Two enumeables which we have used in the past are maps and lists. The **Enum** module lets  perform various operations such as sort, group and filter amonng others.

|Concept | Resource | Prerequisite |
|-----| ----|----------|
|Enummerables | [Documentation](https://hexdocs.pm/elixir/Enum.html) | Maps and Lists|

**The pipe operator:** 

What if someone nests functions like:

F(w(z(y(x))))

It is often confusing to undrrstand this, terefore we use the pipe operator.

In mathematics, we evaluate the expression from the innermost to the outermost.

In Elixir, we use the pipe operator to make it  simpler to evaluate complex functions.

f(x) |> f(y) |> f(z) |> f(w)


The pipe operator takes in the output of one statement and passes it on to the next. 

### Processes 

Each instruction issued to the compiler is treated as process. 

Benefits of Elixir:

**Concurrent and fault-tolerant systems.** All processes run independently thus providing concurrent and fault-tolerant systems.

**Lightweight.** Elixir's porcesses are lightweight both in terms of memory and CPU usage. In this section we'll cover the basics of inter-processor communication.


###### Spawning new processes

###### Sending and Recieving a message

###### Re

### IO and File Systems handling

### Protocols 

### Sigils

### Error handling
#### try, catch and rescue
    
## Conclusion