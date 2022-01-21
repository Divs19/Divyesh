## Lab 01

- Name: Divyesh Ambaliya.
- Email: Ambaliya.2@wright.edu

## Part 1 Answers

1. mkdir DirA
2. mkdir 'Dir B'
3. cd 'Dir B'/
4. DirA uses a better naming convention because spaces create confusion and gives unexpected results.
5. cd ..
   mv 'Dir B' 'DirB'
## Part 2 Answers

1. cd DirA.
   touch test.txt.
2. File contents: vim test.txt
               
                  

```
Hello world!
How are you?
Hope everything is fine1
.
.
.
:wq
```

## Part 3 Answers

1. cp test.txt .hiddentext.txt
2. ls -ld .* (to show hidden files).
    ls -la( to show contents of the file directory).

## Part 4 Answers

1. sudo adduser bob
2. /home/bob
3. No, beacause user is still the admin and for bob to to add or edit the files user needs to add bobo to the admin group 
4. su - bob
5. cd /home/bob
6. yes, bob can add files because we are in bob's home directory so bob can add files.
7. su - divyeshishvarambaliya
8. cd ..


## Part 5 Answers

1. sudo addgroup crew
2. usermod -a -g crew bob
   usermod -a -g crew divyeshishvarambaliya
3. sudo chgrp crew DirA
4. su - bob
5. cd ..
   cd divyeshishvarambaliya
   cd DirA 
   touch bobtest.txt
 6. Beacuse we added DirA to the crew group which can be accessed by both the group.



## Part 6 Answers

1. su - divyeshishvarambaliya
   sudo touch sudowho.txt
2. -rw-r--r--
3. when you use command sudo file is created by root directory so there is readonly file so no contents can be added.   


## Extra Credit

1.
2.
3.
