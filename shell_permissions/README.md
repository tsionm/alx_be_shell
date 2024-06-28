0-iam_betty

This script switches the current user to the user "betty" using the su -b command. It achieves this within 8 characters (su -b) and fulfills the requirement of a two-line script.

    #!/bin/bash: This line specifies the interpreter to be used for the script (bash).
    su -b betty: This command switches the user to "betty" using the su command with the -b option  for 			  a full login shell.

1-who_am_i

This script prints the effective username of the current user by utilizing the whoami builtin command. It adheres to the two-line script requirement.

	#!/bin/bash: This line specifies the interpreter to be used for the script (bash).
        whoami: This builtin command prints the effective username of the current user.
        
        
4-empty

This script creates an empty file named "hello" using the touch command. This script is concise and fulfills the two-line requirement.

	#!/bin/bash: This line specifies the interpreter to be used for the script (bash).
        touch hello: This command creates a new file named "hello" if it doesn't exist. Since no   additional content is provided, the file will be empty.
        


5-execute
This script adds execute permission to the owner of the file "hello" using the chmod +x command.
 This script adheres to the two-line requirement and modifies permissions effectively.
 
 	#!/bin/bash: This line specifies the interpreter to be used for the script (bash).
chmod +x hello: This command modifies the permissions of the file "hello".




6-multiple_permissions

This script grants specific permissions to the file "hello". It adds execute permission to the owner and group owner (u+x,g+x), and read permission to others (o+r) using the chmod command. This script adheres to the two-line requirement and effectively modifies permissions for different user categories.
        
        #!/bin/bash: This line specifies the interpreter to be used for the script (bash).
chmod u+x,g+x,o+r hello: This command modifies the permissions of the file "hello".



9-John_Doe

This script sets the exact mode of the file "hello" according to the provided specifications. It avoids commas and uses chmod with specific assignments (=) to set precise permissions for owner, group, and others. This script adheres to the two-line requirement.
	#!/bin/bash: This line specifies the interpreter to be used for the script (bash).
chmod u=rwx,g=rx,o=wx hello: This command modifies the permissions of the file "hello".




