# SPARK
A simple programming language hoping to be used for Game dev

Printing a text to console
```WRITE("Hello World!");```

Creating a variable
```VAR myvariable = 025;``` int
```VAR myvariable = helloguys;``` string

Arithemetic calculations
```WRITE(1+1);```

Creating a function
```FN CoolFunction();```

Changing value of a variable
```SET VAR myvariable = 555;```

Adding actions to functions
```SET FN CoolFunction = WRITE("Hello");```

Call a function
```CALL CoolFunction();```

Adding forever loop
```FOREVER():WRITE(myvariable);```

Random example of all features shown
```
FN SayHi();
FN RunFunctions();
VAR hiText = Hi from Spark;
VAR anotherText = Spark is very cool! lol just kidding;
VAR memeboy = Spark users mew in skibidi!;
VAR laugh = hehe;
SET FN SayHi = WRITE(hiText);
SET FN SayHi = WRITE(anotherText);
SET FN RunFunctions = WRITE(memeboy);
SET FN RunFunctions = CALL SayHi();
SET VAR laugh = haha;
CALL RunFunctions();
FOREVER():WRITE(laugh);
```
has been under dev of 1 and (1/2) days

