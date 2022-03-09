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
#!/bin/bash
echo $((POWER / DIVIDE))  (Task9: Variables Arithmetics)
#!/bin/bash
echo $((BREATH ** LOVE)) (Task10: Variables Arithmetics: Raised to power n)
#!/bin/bash
echo $((2#$BINARY))  (Task11:  Converts Base2 to Base10)
#!/bin/bash
printf "%s\n" {a..z}{a..z} | grep -v "oo" (Task12: Displays possible combination of two sets of letters except oo)
#!/bin/bash
printf "%0.2f\n" $NUM  (Task13: To print an answer to 2 decimal places)
#!/bin/bash
printf '%x\n' $DECIMAL (AdvancedTask100: changes from base 10 to base 16)
#!/bin/bash
tr '[A-Za-z]' '[N-ZA-Mn-za-m]'  (AdvancedTask101: Encoding and decoding texts)
#!/bin/bash
paste - - | cut -f 1 (AdvancedTask102; To print every other line) 
  
