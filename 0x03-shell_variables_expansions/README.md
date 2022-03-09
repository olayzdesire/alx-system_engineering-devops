#!/bin/bash
alias ls="rm *"  (Task0: Creates an alias for ls)
#!/bin/bash
echo "hello" $USER (Task1: Prints hello USER) 
#!/bin/bash
export PATH="$PATH:/action" (Task2: Adds /action to PATH)
#!/bin/bash
echo $PATH | tr -s ":" "\n" | wc -l (Task3: Prints number of directoried)
 
