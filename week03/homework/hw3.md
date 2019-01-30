# EECS 201 HW 3
uniqname: mayakh

## Question 1
``` 1
The ls command no longer works.
```

## Question 2
``` 2
 /bin/ls works to display everything. 
```

## Question 3
``` 3
cd still works, because the PATH command sets up a search up executable files, ls doenst work, but the terminal can still change directories
```

## Question 4
``` 4
$? is used to find the return value of the last executed command, for example if you were to to ls something, the $? would be able to know the values of the current executable directories.
```

## Question 5
``` 5
$1 is a positional argument in a script, it gets the first argument from the command line. This would be especially useful for scripts that may excute different commands based on command line arguments.
```

## Question 6
``` 6
 gcc main.c –o HelloWorld
 output = $(./HelloWorld)
 expected = "Hello World!"
 if ["$output" == "$expected"]
 then
    echo "All tests passed"
 else
    echo "Test failed. Expected output >>$expected << , got output >>$output<<"
 fi
 
```

## Question 7
``` 7
.bashrc would change, export PATH=$PATH:~/bin.
```

### Question 8
``` 8
probably around 2 hours. 
```

