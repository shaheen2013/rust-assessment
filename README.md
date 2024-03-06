**Day - 1**

1. Set up rust development environment using rustup and build a simple project that prints “Hello world” in the terminal
2. Learn about rust data types, scope, and functions

**Day - 2**

1. Learn ownership and borrowing in rust
2. Learn fundamentals of struct, and enums
3. Learn rust attributes
4. Learn basics of rust lifetime

**Day - 3**

1. Argument parsing
2. `std::path::Path `and File I/O
3. Program arguments and argument parsing

**Day - 4**

1. Clone this project: —
2. Add a function that processes command line arguments
3. Take input from the command line in the following format:
    1. `process_monitor -monitorFile /path/to/given/monitors.json/file`
4. Create one or more data structures in rust for storing the data from the monitors.json file in a similar format
5. Now, create a struct for result in the format given below

    ```
    Result
        integer value
        integer processed_at
    ```

**Day - 5**

1. Prepare an instance to hold the JSON data from the monitors.json file and put random results in each monitor
    1. Put any numeric value in the value field of the result instance
    2. Put the current timestamp(time passed since unix epoch) in seconds
2. Convert this data to JSON again
3. Find any suitable package/library for the rust object to JSON conversions and vice versa
4. Handle possible error cases so that your program doesn’t panic in the runtime
