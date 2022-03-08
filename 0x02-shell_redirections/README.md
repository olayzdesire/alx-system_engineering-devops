#!/bin/bash
echo Hello, World (Task0: Printing “Hello, World”)
#!/bin/bash
echo "\"(Ôo)'" (Task1: Prnting the text "(Ôo)')
#!/bin/bash
cat /etc/passwd (Task2: Show contents of file)
#!/bin/bash
cat /etc/passwd /etc/hosts (Task3: Show contents of 2 files)
#!/bin/bash
tail -10 /etc/passwd (Task4: Display last 10 lines of a file)
#!/bin/bas#h
head -10 /etc/passwd (Task5: First 10 lines of a file)
#!/bin/bash
head -3 iacta | tail +3 (Task6: To show the 3rd line of file iacta)
#!/bin/bash
echo "Best School" > " \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)"  (Task7: adding content to a file) 
#!/bin/bash
ls -al > ls_cwd_content (Task8: Displaying the result of the command ls-al in a file)
#!/bin/bash
tail -1 iacta >> iacta (Task9: Duolicating last line of the file iacta)
#!/bin/bash
find -name "*.js" -type f -delete  (Task10: finds and delete all .je files)
#!/bin/bash
find -mindepth 1 -type d | wc -l  (Task11:lists all directories exluding current direcory) 
#!/bin/bash
ls -t | head -10 (Task12: To display 10 newesr files) 
#!/bin/bash
sort |uniq -u (Tasm13: Sorts uniquely)
#!/bin/bash
grep root /etc/passwrd (Task14: show lines having 'root')
#!/bin/bash
grep -c bin /etc/passwd (Task15: Counts numbers of lines containing bin) 
#!/bin/bash
grep root /etc/passwd --after-context=3 (Task16: Printing 3lines after grep results) 
#!/bin/bash
grep -v bin /etc/passwd  (Task17: Printing lines not having bin) 
#!/bin/bash
grep '^[[:alpha:]]' /etc/ssh/sshd_config  (Task18: Prints all lines in the file starting with alphabet and capital) 
#!/bin/bash
tr A Z | tr c e  (Task19: Replacing letters A Z with c e)
#!/bin/bash
tr -d C | tr -d c (Task20: deleting -C and -c) 
#!/bin/bash
rev    (Task21: get reveese input) 
#!/bin/bash
cut -d : -f 1,6 /etc/passwd | sort (to view users and home direcrectories) 
