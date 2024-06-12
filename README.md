# VORTEX
A simple programming language hoping to be used for Game dev

Printing a text to console
```WRITE("Hello World!");```

Creating a variable
```VAR myvariable = 025;``` int
```VAR myvariable = helloguys;``` string

Arithemetic calculations
```WRITE(1+1);```


Changing value of a variable
```SET myvariable = 555;```

Adding build-in-function to functions
```
FN Lol(){
    WRITE("HAHA");
}
```

Call a function
```CALL CoolFunction();```

Adding forever loop
```FOREVER():WRITE(myvariable);```


Simple calculator in spark
```
VAR a = 0;
VAR b = 0;

WRITE("Type a number 1 ");
READ(a);
WRITE("Type a number 2 ");
READ(b);

FN add() {
    WRITE("Added Answer");
    WRITE(a + b);
}

FN substract() {
    WRITE("Substracted Answer");
    WRITE(a - b);
}

FN multiply() {
    WRITE("Multiplied Answer");
    WRITE(a * b);
}

FN divide() {
    WRITE("Divided Answer");
    WRITE(a / b);
}
CALL add();
CALL substract();
CALL multiply();
CALL divide();
```

has been under dev of 1 and (1/2) days


