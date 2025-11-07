```
/home $ cd node/
~ $ pwd
/home/node
~ $ mkdid commands
/bin/sh: mkdid: not found
~ $ mkdir commands
mkdir: can't create directory 'commands': File exists
~ $ pwd
/home/node
~ $ ls-a
/bin/sh: ls-a: not found
~ $ ls -a
.               .cache          .n8n            project
..              .dotnet         .vscode-server  test
.ash_history    .gitconfig      commands
~ $ mkdir test
mkdir: can't create directory 'test': File exists
~ $ ls -l
total 12
drwxr-sr-x    2 node     node          4096 Nov  7 03:43 commands
drwxr-sr-x    2 node     node          4096 Nov  7 03:03 project
drwxr-sr-x    2 node     node          4096 Nov  7 03:41 test
~ $ mkdir notes
~ $ cd notes
~/notes $ pwd
/home/node/notes
~/notes $ cd ..
~ $ pwd
/home/node
~ $ mkdir -p  image videos docs
~ $ ls -la
total 68
drwxr-sr-x    1 node     node          4096 Nov  7 03:49 .
drwxr-xr-x    1 root     root          4096 Aug  4 09:12 ..
-rw-------    1 node     node          1153 Nov  7 03:49 .ash_history
drwxr-sr-x    4 node     node          4096 Nov  6 07:47 .cache
drwxr-sr-x    3 node     node          4096 Nov  6 07:47 .dotnet
-rw-r--r--    1 node     node           292 Nov  7 02:57 .gitconfig
drwxr-sr-x    1 node     node          4096 Nov  7 02:08 .n8n
drwxr-sr-x    6 node     node          4096 Nov  6 07:47 .vscode-server
drwxr-sr-x    2 node     node          4096 Nov  7 03:43 commands
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 image
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 notes
drwxr-sr-x    2 node     node          4096 Nov  7 03:03 project
drwxr-sr-x    2 node     node          4096 Nov  7 03:41 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 videos
~ $ cd docs
~/docs $ ls -la
total 12
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 .
drwxr-sr-x    1 node     node          4096 Nov  7 03:49 ..
~/docs $ cd ..
~ $ ls -la
total 68
drwxr-sr-x    1 node     node          4096 Nov  7 03:49 .
drwxr-xr-x    1 root     root          4096 Aug  4 09:12 ..
-rw-------    1 node     node          1181 Nov  7 03:50 .ash_history
drwxr-sr-x    4 node     node          4096 Nov  6 07:47 .cache
drwxr-sr-x    3 node     node          4096 Nov  6 07:47 .dotnet
-rw-r--r--    1 node     node           292 Nov  7 02:57 .gitconfig
drwxr-sr-x    1 node     node          4096 Nov  7 02:08 .n8n
drwxr-sr-x    6 node     node          4096 Nov  6 07:47 .vscode-server
drwxr-sr-x    2 node     node          4096 Nov  7 03:43 commands
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 docs
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 image
drwxr-sr-x    2 node     node          4096 Nov  7 03:48 notes
drwxr-sr-x    2 node     node          4096 Nov  7 03:03 project
drwxr-sr-x    2 node     node          4096 Nov  7 03:41 test
drwxr-sr-x    2 node     node          4096 Nov  7 03:49 videos
```