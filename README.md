1)root@f798856ead4d:/home# ls
  celery  chairs  classic  create  dir1  dir2  dir3  file3.txt  practice1  records  test  vegetables
  root@f798856ead4d:/home# mkdir classics
  root@f798856ead4d:/home# ls
  celery  chairs  classic  classics  create  dir1  dir2  dir3  file3.txt  practice1  records  test  vegetables
  
2)root@f798856ead4d:/home# rmdir classics
  root@f798856ead4d:/home# ls
  celery  chairs  classic  create  dir1  dir2  dir3  file3.txt  practice1  records  test  vegetables
    
3)root@f798856ead4d:/home# uname -a
  Linux f798856ead4d 4.19.0-16-amd64 #1 SMP Debian 4.19.181-1 (2021-03-19) x86_64 x86_64 x86_64 GNU/Linux
  
4)root@f798856ead4d:/home# uname -s
  Linux

5)root@f798856ead4d:/home# uname -r
  4.19.0-16-amd64
  
6)root@f798856ead4d:/home# date
  Fri Oct 15 15:47:41 MSK 2021
  
7)

8)

9)/clean

10)root@f798856ead4d:/home#pwd
   /home
   
11)root@f798856ead4d:/home# cd ~
   root@f798856ead4d:~# ls
   classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2
   
12)root@f798856ead4d:~# ls  //отображает содержимое каталога
   classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2
   root@f798856ead4d:~# ls -R  //рекурсивно отображает содержимое поддиректорий
   .:
   classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

   ./classics:

   ./dir1:
   f1

   ./dir2:

   ./dir3:

   ./test:
   subtest

  ./test/subtest:

   ./test1:
   subtest

  ./test1/subtest:

   ./test2:
   subtest

   ./test2/subtest:
   
13)root@f798856ead4d:~# ls -a
   .  ..  .bash_history  .bashrc  .local  .profile  classics  dir1  dir2  dir3  file1  file2  file3  t.sh  test  test1  test2

14)root@f798856ead4d:~# ls -l
   total 32
   drwxr-xr-x 2 root root 4096 Oct 15 15:52 classics
   drwxr-xr-x 2 root root 4096 Oct 13 16:19 dir1
   drwxr-xr-x 2 root root 4096 Oct 13 16:16 dir2
   drwxr-xr-x 2 root root 4096 Oct 13 16:16 dir3
   -rw-r--r-- 1 root root    0 Oct 13 16:20 file1
   -rw-r--r-- 1 root root    0 Oct 13 16:20 file2
   -rw-r--r-- 1 root root    0 Oct 13 16:20 file3
   -rw-r--r-- 1 root root  366 Oct  6 15:54 t.sh
   drwxr-xr-x 3 root root 4096 Oct 13 15:32 test
   drwxr-xr-x 3 root root 4096 Oct 15 15:36 test1
   drwxr-xr-x 3 root root 4096 Oct 15 15:42 test2

15)root@f798856ead4d:~# ls -F
   classics/  dir1/  dir2/  dir3/  file1  file2  file3  t.sh  test/  test1/  test2/

16)root@f798856ead4d:~# cd classics

17)
