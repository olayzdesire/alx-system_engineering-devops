#!/bin/bash
su betty  (Task0: Switching User)
#!/bin/bash
whoami   (Task1: Getting the effective username of the current user)
#!/bin/bash
groups (Task2: Knowing the groups a current user belong)
#!/bin/bash
chown betty hellp (Task3: Changes Ownership to betty)
#!/bin/bash
touch hello (Task4: Creates an empty file)
#!/bin/bash
chmod u+x hello (Task5: gives execute permission to file owner)
#!/bin/bash
chmod u+x,g+x,o+r hello (Task6: gives different permissions to different users)
#!/bin/bash
chmod ugo+x hello (Task7: Gives execuive peemission to differnt users)
#!/bin/bash
chmod 007 hello(Task8: Gives no permission to ownee and groups, full permissions to others)
#!/bin/bash
chmod 753 hello (Task9: Gives different permissions to different users)
#!/bin/bash
chmod --reference=olleh hello  (Task10: Sets the new file's mode as reference mode)
#!/bin/bash
chmod a+X * (Task 11: Sets execute permissions for subdirectories and current folders)
#!/bin/bash
mkdir -m 751 mydir (Task12: creates a directory - my dir with permission 751)
#!/bin/bash
chgrp school hello (Task13: Changes group from School to Hello) 
#!/bin/bash
chown vincent:staff *
#!/bin/bash
chown vincent:staff _hello (Task14: Changes ownership to Symbolic link file)
#!/bin/bash
chown --from=guillaume betty hello (Task15: Changes ownership with IF ONLY)
#!/bin/bash
telnet towel.blinkenlights.nl (Task17: Plays StarWars Episode IV in the terminal)  
