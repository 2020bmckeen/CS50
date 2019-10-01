# Collection of notes in the C language

Scratch:   Say(hello, world)

```C
printf("hello, world\n");
```

All printed words are called strings and strings are enclosed by "string"<br>
\n tells computer to start a new line <br>
The ; is like the period at the end of a sentence. It tells the computer that thus is the end of the statement.

Scratch:   Set counter to 0

```C
int counter = 0;
```

In C, you must declare the type of variable you are creating

Scratch:  change counter by 1

```C 
counter = counter + 1; #add any number to counter
counter += 1; #add any number to counter
counter++; #only adds plus 1 to counter
```

Single "=" does not mean "equals" it means "assigns" 

Scratch: If x<y then say x is less than y

```C
if (x<y)
{
    print f("x is less than y\n");
}
```

Scratch: If x<y then say x is less than y else say x is not less than y

```C
if (x<y)
{
    printf("x is less than y\n");
}
else
{
    printf("x is not less than y\n");
}
```

Scratch x<y then say x is less than y else if x.y then say x is greater than y else if x=y then say x is equal to y

```C
if (x<y)
{
    printf("x is less then y\n");
}
else
{
    printf("x is greater than y/n");
}
else if (x==y)
{
    printf("x is equal to y/n");
}
