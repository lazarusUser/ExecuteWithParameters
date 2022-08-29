# ExecuteWithParameters
Purpose: testing programs automatically: 
Pure Lazarus/FPC
uses process{TProcess}

- FName_executable.exe
- FName_input.txt  //a file to read ipnut parameters from 
- FName_output.txt //a file to write output to

The program must 
- take file names, 
- prepare parameters
- execute another program with parameters
- capture output
- write output to log/FName_output.txt
