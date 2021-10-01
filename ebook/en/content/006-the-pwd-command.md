 # The `PWD` command

The `pwd` stands for Print Working Directory. It prints the path of the working directory, starting from the root.
  
Example:

```
pwd   
```  

Syntax:

```
pwd [OPTION] 
```  

### Options:
      -L        print the value of $PWD if it names the current working
                directory
      -P        print the physical directory, without any symbolic links

By default, `pwd' behaves as if `-L' were specified.
 
