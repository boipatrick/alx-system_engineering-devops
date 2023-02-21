<h1>A list of scripts that perform different tasks</h1> 
<p>su betty - switches the current user to the user betty</p>
<p>id -un - prints the effective username of the current user</p>
<p>groups - prints all the groups the current user is part of</p>
<p>chown betty hello - changes the owner of the file hello to the user betty</p>
<p>touch hello - creates an empty file named hello</p>
<p>chmod u+x hello - adds execute permission to the owner of the file hello</p>
<p>chmod u+x,g+x,o+r hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello</p>
<p>chmod ugo+x hello - adds execution permission to the owner, the group owner and the other users, to the file hello</p>
<p>chmod 753 hello - sets the mode of the file hello to -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello</p>
<p>chmod --reference=olleh hello - sets the mode of the file hello the same as olleh’s mode</p>
<p>chmod -R ugo+X - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users</p>
<p>mkdir -m 751 mydir - creates a directory called mydir with permissions 751 in the working directory</p>
<p></p>chgrp school hello - changes the group owner to school for the file hello
<p>chown -hR vincent:staff - changes the owner to vincent and the group owner to staff for all the files and directories in the working directory</p>
<p>chown -h vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively</p>
<p>chown --from=guillaume betty hello - changes the owner of the file hello to betty only if it is owned by the user guillaume</p>
<p>telnet towel.blinkenlights.nl -  script that will play the StarWars IV episode in the terminal</p>


