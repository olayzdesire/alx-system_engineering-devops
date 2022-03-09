#!/bin/bash
alias ls="rm *"  (Task0: Creates an alias for ls)
#!/bin/bash
echo "hello" $USER (Task1: Prints hello USER) 
#!/bin/bash
export PATH="$PATH:/action" (Task2: Adds /action to PATH)
#!/bin/bash
echo $PATH | tr -s ":" "\n" | wc -l (Task3: Prints number of directoried)
#!/bin/bash
printenv (Task4: Displays all available Variables) 
#!/bin/bash
set (Task5: Prints all info about local variables) 
#!/bin/bash
BEST="School" (Task6: Creates a new variable)
#!/bin/bash
export BEST="School"  (Task7: Creating a global Variable)
#!/bin/bash
echo -e $((128 + TRUEKNOWLEDGE))  (Task8: addition arithmetic)
 
