Readme.md about shell_permission done in Holbertonschool Lille by sadat babak

file: 0-iam_betty => switch the current user to betty. i used (su username(betty)) command to switch user.

Added a script file: 1-who_am_i => it print the username of current user. Command used: whoami

file: 2-groups, Command added: groups =>it will show the groups that the user is part of.(secound commit)

 file: 3-new_owner, command used: sudo(to run in administrator) chown(to change owner) username(betty) filename(betty) => it will change the owner of file(hello) to user(betty).

file: 4-empty, command used: touch filename(hello) => it will creat a new empty file(hello).

file: 5-execute, command used: chmod(change/modify user access right) u(user)+(add)x(execute) filename(hello).

file:6-mulitple_permissions, command used: chmod(modify file acess right) 7(uese rwx)6(group r-x)4(other r--) filename(hello) => it will change file acess right user rwx groupe r-x and other only read r--.

file: 7-everbody, command used: chmod a(all)+x(execution) filename(hello) => it will give the right to execute the file(hello) for eveyone(u,g,o).

added File:8-James_Bond, command used: chmod 007(no permission to user, no permission to groups and all permission to others) filename(hello) => it will give all permission to other but no P to user and groups..

Added file: 9-John_Doe, command used: chmod 7(rwx)5(r-x)3(-wx) filename(hello) => it will change the file(hello) access right in his respected order(demanded).

file/ 10-mirror_permissions, command added: chmod --reference(as it name stats)=referance filename(olleh) file(hello) => here the file(hello) will be reference to file(olleh) and copy his access right mode.

Added file: 11-directories_permissions, command added: chmod(change file acces right)-R(for file change) u(user)+X(execute permission to subdirectory of the current directory) .(for current directory) => it give permission to execute subdirectory of the current directory to all(u,g,o).

File: 12-directory_permissions, command added: mkdir(to make directory) -m(for mode) directoryname(my_dir) => it will creat ad directory(my_dir) with given permission mode (751).


Added File:13-change_group, command used: chgrp(change group) groupowner(school) filename(hello) => it will change the group owner of file(hello) to groupowner(school).

Added file: 14-chang_owner_and_group, command used: chown(change owner)-R(operate on files and directories) vincent(user):staff(group) .(current directory) => it will change the ownership of user to vincent and group to stafff.

Added file: 15-symbolic_link_permissions, command added: chown(change owner) -h(affect  symbolic links instead of any referenced file) user(vincent):group(staff) linkfile(_hello) => the linkfile (hello) will change his user(vincent) and group(staff).

file: 16-if_only, command used: chown --from=owneroffile(guillaume) targetedowner(vincent) filename(hello) => it will change the owner of the file(hello) to vincent if the owener is guillaume.
