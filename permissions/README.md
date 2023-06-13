0-iam_betty : script that switches the current user to the user betty.
1-who_am_i : script that prints the effective username of the current user.
2-groups: script that prints all the groups the current user is part of.
3-new_owner: script that changes the owner of the file hello to the user betty.
4-empty:script that creates an empty file called hello
5-execute : script that adds execute permission to the owner of the file hello.
6-multiple_permissions: script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody : script that adds execution permission to the owner, the group owner and the other users, to the file hello
8-James_Bond : script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions

9-John_Doe : script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

10-mirror_permissions : script that sets the mode of the file hello the same as olleh’s mode.
