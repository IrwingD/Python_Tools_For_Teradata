# Python_Tools_For_Teradata

## db_child.exe

#### What this script does:
The program takes a view name as input and gives you a report on it like so:
List of Tables
List of Views
Size of tables in MB
Stats on Tables

### Installation

Edit the file list_file.txt to list your object(s) - current version only supports a single view as an input  
Edit the file logon_file.txt to use your credentials and server name.  

### pre requisites
This will only work on Windows  
You need to have bteq installed on your machine  
you need to have access to the Teradata Database you are querying  

### Usage

On Windows either double click the db_child.exe file or run it from cmd  

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

### History

7/26 - uploaded first version to github

### Credits

This was my first serious github project so thanks to zenorocha for his markdown template
https://gist.github.com/zenorocha