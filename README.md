# commands
1Q. Your first challenge is to print "hello world" on the terminal in a single command.
A. echo hello\ world

2Q. Print the current working directory.
A. pwd 

3Q. List names of all the files in the current directory, one file per line. 
A. ls
      01-take.txt
      02-the.txt
      03-command.txt
      04-challenge.txt

4Q. There is a file named access.log in the current directory. Print the contents.
A. cat access.log

163.56.115.58 - - [09/Jan/2017:22:29:57 +0100] "GET /posts/2/display HTTP/1.0" 200 3240
75.113.188.234 - - [09/Jan/2017:22:30:43 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 1116
69.16.40.148 - - [09/Jan/2017:22:34:33 +0100] "GET /pages/create HTTP/1.0" 500 3471
225.219.54.140 - - [09/Jan/2017:22:35:30 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 500 2477
207.243.19.2 - - [09/Jan/2017:22:38:03 +0100] "GET /bar/create HTTP/1.0" 200 1116
199.37.62.156 - - [09/Jan/2017:22:42:18 +0100] "GET /posts/1/display HTTP/1.0" 200 2477
55.74.240.123 - - [09/Jan/2017:22:44:25 +0100] "POST /posts/1/display HTTP/1.0" 200 3471
251.111.109.143 - - [09/Jan/2017:22:49:02 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 2477
101.163.230.250 - - [09/Jan/2017:22:52:31 +0100] "DELETE /posts/2/display HTTP/1.0" 404 2477
200.19.168.148 - - [09/Jan/2017:22:57:11 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 3471

5Q. Print the last 5 lines of "access.log".
A.  tail -5 access.log

 199.37.62.156 - - [09/Jan/2017:22:42:18 +0100] "GET /posts/1/display HTTP/1.0" 200 2477
55.74.240.123 - - [09/Jan/2017:22:44:25 +0100] "POST /posts/1/display HTTP/1.0" 200 3471
251.111.109.143 - - [09/Jan/2017:22:49:02 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 2477
101.163.230.250 - - [09/Jan/2017:22:52:31 +0100] "DELETE /posts/2/display HTTP/1.0" 404 2477
200.19.168.148 - - [09/Jan/2017:22:57:11 +0100] "GET /posts/foo?appID=xxxx HTTP/1.0" 200 3471

6Q. Create an empty file named take-the-command-challenge in the current working directory
A.  touch take-the-command-challenge

7Q. Create a directory named tmp/files in the current working directory
A.  mkdir tmp/files -p 

8Q. Copy the file named take-the-command-challenge to the directory tmp/files
A.  cp take-the-command-challenge tmp/files

9Q.  move the file named take-the-command-challenge to the directory tmp/files
A.   mv take-the-command-challenge tmp/files

10Q.  A symbolic link is a type of file that is a reference to another file.
      Create a symbolic link named take-the-command-challenge that points to the file tmp/files/take-the-command-challenge.
A.   ln -s tmp/files/take-the-command-challenge

