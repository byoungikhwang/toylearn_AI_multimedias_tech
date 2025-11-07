```
C:\commands> md test
    디렉터리: C:\commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:45                test

PS C:\commands> md notes


    디렉터리: C:\commands

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:46                notes

PS C:\commands> md images,videeos,docs


    디렉터리: C:\commands

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:46                images
d-----      2025-11-06   오후 5:46                videeos
d-----      2025-11-06   오후 5:46                docs

PS C:\commands> ls

    디렉터리: C:\commands
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:46                docs
d-----      2025-11-06   오후 5:46                images
d-----      2025-11-06   오후 5:46                notes
d-----      2025-11-06   오후 5:45                test
d-----      2025-11-06   오후 5:46                videeos

```
디렉토리 삭제
//  PS C:\> rd docs,images,notes,test,videeos
// cd ..
// PS C:\> rd commands
// ls -l

```