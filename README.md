# Get_Next_Line - @HiveHelsinki

**Get Next Line is a project at Hive Helsinki coding school.**

![alt text](https://user-images.githubusercontent.com/49685048/71586078-91e76e80-2b21-11ea-8156-c9f013ad8302.png)

This projects is about creating a function that, allows to read a line ending with a newline character ('\n') from a file descriptor, without knowing its size beforehand. 

**Usage:**
* get_next_line is a function that reads data from a file descriptor line by line.
* calling the function get_next_line in a loop reads the text from file descriptor one line at a time until the end of the text.


**Return value:**
* return 1 when it read a line
* return 0 when it finished reading a file
* return -1 when an error occurs
