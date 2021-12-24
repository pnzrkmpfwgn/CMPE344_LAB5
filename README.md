Tiny Web server
Dave O'Hallaron
Carnegie Mellon University

This is the home directory for the Tiny server, a 200-line Web
server that we use in "15-213: Intro to Computer Systems" at Carnegie
Mellon University.  Tiny uses the GET method to serve static content
(text, HTML, GIF, and JPG files) out of ./ and to serve dynamic
content by running CGI programs out of ./cgi-bin. The default 
page is home.html (rather than index.html) so that we can view
the contents of the directory from a browser.

Tiny is neither secure nor complete, but it gives students an
idea of how a real Web server works. Use for instructional purposes only.

The code compiles and runs cleanly using gcc 2.95.3 
on a Linux 2.2.20 kernel.

To install Tiny:
   Type "tar xvf tiny.tar" in a clean directory. 

To run Tiny:
   Run "tiny <port>" on the server machine, 
	e.g., "tiny 8000".
   Point your browser at Tiny: 
	static content: http://<host>:8000
	dynamic content: http://<host>:8000/cgi-bin/adder?1&2

Files:
  tiny.tar		Archive of everything in this directory
  tiny.c		The Tiny server
  Makefile		Makefile for tiny.c
  home.html		Test HTML page
  godzilla.gif		Image embedded in home.html
  README		This file	
  cgi-bin/adder.c	CGI program that adds two numbers
  cgi-bin/Makefile	Makefile for adder.c
	
	
	# Moddified Adder
	![Modified adder](https://user-images.githubusercontent.com/61189367/147355431-931dcdf1-3335-47e8-b4d5-03c1740f5f7d.PNG)
	
	# Moddified HTML
	![Moddified HTML](https://user-images.githubusercontent.com/61189367/147355449-7a7f2806-b504-4a01-a728-49692a1a9b8e.PNG)
	
	# Compiled adder
	![Compiling Adder](https://user-images.githubusercontent.com/61189367/147355463-57a55030-cdad-437c-b1c1-36066df4a7f5.PNG)
	
	# Running tiny on port 3000
	![Running tiny on port 3000](https://user-images.githubusercontent.com/61189367/147355483-a474ab1f-9b3f-467a-8e2b-b40eddb10317.PNG)
	
	# Our Website is running
	![Our website running](https://user-images.githubusercontent.com/61189367/147355500-e0e176a0-280e-48a0-acdd-1efb14033501.PNG)
	
	# Result
	![Result](https://user-images.githubusercontent.com/61189367/147355509-d6422983-a8ba-4b13-8e7c-c8bceee81dda.PNG)

