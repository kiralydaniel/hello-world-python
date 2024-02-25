# Hello, World!
## Modify helloworld.py so that it prints out Hello, World! to the console. Do not write any functions yet.

    Running helloworld.py prints out Hello, World! to the console.

    The source code of helloworld.py contains no function definitions.


## Hello, Function!
Create and call a function in hellofunction.py which prints Hello, World! to the console.

    Running hellofunction.py prints out Hello, World! to the console.

    The source code of hellofunction.py defines and calls a say_hello() function which is responsible for printing the Hello, World! message.


## Hello, Return!
Create and call two functions in helloreturn.py - one should return the Hello, World! string to the second function which is responsible for printing it to the console.

    Running helloreturn.py prints out Hello, World! to the console.

    The source code of helloreturn.py defines a get_hello_message() function which does not print anything but returns the Hello, World! message.

    The source code of helloreturn.py defines and calls a say_hello() function which is responsible for printing the message returned by get_hello_message().


## Hello, Input!
Create and call two functions in helloinput.py - one should ask for the name of the user and an another which prints the custom greeting message to the console.

    Running helloinput.py prints What's your name?, asks for user input, and using the input prints Hello, <name>! to the console.

    Running helloinput.py asks What's your name?, and if the user does not enter anything, it prints Hello, World! to the console.

    The source code of helloinput.py defines a get_hello_message() function which prints What's your name?, and returns Hello, <name>! using the user input (or Hello, World! for an empty input).

    The source code of helloinput.py defines and calls a say_hello() function which is responsible for printing the message returned by get_hello_message().


## Hello, Argument!
Capitalize the user's diplayed name in a reorganized helloargument.py that separates the input collection and the message assembly parts.

    Running helloargument.py prints What's your name?, asks for user input, and using the input prints Hello, <Name>! to the console (<Name> is capitalized).

    Running helloargument.py asks What's your name?, and if the user does not enter anything, it prints Hello, World! to the console.

    The source code of helloargument.py defines a get_user_name() function which prints What's your name?, and returns the capitalized version of the user's input string.

    The source code of helloargument.py defines a get_hello_message(name) function which returns Hello, <name>! using the incoming argument (or Hello, World! for an empty argument).

    The source code of helloargument.py defines and calls a say_hello() function which is responsible for printing the message after collecting the returned values from the other two functions.