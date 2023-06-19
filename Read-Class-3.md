## File and Stream I/O
File and stream I/O, which stands for Input/Output, involves reading from and writing to files or other input/output streams using the classes provided in the System.IO namespace. It enables interaction with data stored in files or working with various input/output devices like the console, network sockets, and memory streams.

## Write to a file
To write to a file, you can create an instance of the StreamWriter class, which handles writing characters to a stream. Open the file in write mode using the StreamWriter constructor and specify the file path. Then, use the Write or WriteLine method of the StreamWriter object to write data to the file. Finally, close the file.

## Read to a file
For reading from a file, create an instance of the StreamReader class, responsible for reading characters from a stream. Use the Read or ReadLine method of the StreamReader object to read data from the file. To release resources, close the file by calling the Dispose method of the StreamReader or utilizing a using statement.
