title: "Code Highlight"
date: "2014-03-15 20:17:16"
categories: Tests
toc: true
---

## C ##

``` c
// C
#include <stdio.h>
int main(void)
{
    printf("Hello World\n");
    return 0;
}
```

## C++ ##

``` c++
// C++
#include <iostream.h>
int main(void)
{
    cout << "Hello World" << endl;
    return 0;
}
```

<!-- more -->

## JAVA ##

``` java
class helloWorld
{
    public static void main(String args[])
    {
        System.out.println("Hello World");
    }
}
```

## Assembler ##

``` assembler
#include <stdio.h>

char format[] = "%s %s\n";
char hello[] = "Hello";
char world[] = "world";
void main( void )
{
   __asm
   {
      mov  eax, offset world
      push eax
      mov  eax, offset hello
      push eax
      mov  eax, offset format
      push eax
      call printf
      pop  ebx
      pop  ebx
      pop  ebx
   }
}
```

## C# ##

``` C#
// Hello World .NET

#using <mscorlib.dll>
using namespace System;

int _tmain()
{
    Console::WriteLine(S"Hello World");
    return 0;
}
```

## Erlang ##

``` erlang
-module(hello).
-export([world/0]).

world() -> io:format("Hello World").
```

## Ruby ##

``` ruby
#!/usr/local/bin/ruby -w
puts "Hello World"
```

## BASIC ##

``` basic
// Texas Instruments TI-81 BASIC
Prgm1:HELLO...
:Disp "HELLO WORLD"
```

## Perl ##

``` perl
#!/usr/bin perl -w  
print ("Hello World");  
```

## Python ##

``` python
#!/bin/python
print("Hello World")
```

## Bash ##

``` bash
#!/bin/bash
echo "Hello World"
```

## Brainfuck ##

``` brainfuck
>+++++++++[<++++++++>-]<.>+++++++[<++++>-]<+.+++++++..+++.[-]
>++++++++[<++++>-] <.>+++++++++++[<++++++++>-]<-.--------.+++
.------.--------.[-]>++++++++[<++++>- ]<+.[-]++++++++++.
```

## php ##

``` php
<?="Hello world\n" ?> 
```

## Pascal ##

``` pascal
Program HelloWorld;

Begin
  Writeln ('Hello World!');
End.
```

## Delphi ##

``` delphi
// Delphi, thanks to C0derr
program Project1;
uses
  qdialogs;
const
  s='Hello, World!';
begin
  showmessage(s);
end.
```
