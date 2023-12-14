# lua-exceptions

A lua implementation of python's exceptions.

## How to use:
Raise an exception by using ```module.raise(__exception: string, __error_message: string)```

Catch an exception by using ```module.catch(__exception: string, __exception_handler: (any) -> (any))```

Define an exception by using ```module.new_exception(__body: string)```
