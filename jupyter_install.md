---
title: "Installing Python and Jupyter"
author:
- Killian O'Brien
- 6G6Z0024 Applied Cryptography
date: October 2025
---
<head>
		<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
		<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
		<link rel="preconnect" href="https://fonts.googleapis.com">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital@0;1&display=swap" rel="stylesheet">
		<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Serif&display=swap" rel="stylesheet">
        <style>
            body {
			 /* font-family: 'IBM Plex Sans', sans-serif; */
			 font-family: 'IBM Plex Serif', serif;
             }
             a {
  color: blue;
}
a:visited {
  color: green;
}
a:hover {
  color: hotpink;
}

</style>
</head>

There are many ways to install Python and associated programs and it can get complicated with having many different versions of Python and associated libraries installed in different *environments* on your computer. 

These instructions are the simplest way, on a Windows operating system, to go from having no Python or Jupyter installed to having a basic set-up that will allow you to work on your Jupyter notebooks like you do in the timetabled labs. 

Follow along with my video as I perform the steps on a Windows computer, or just jump to the main steps below the video and follow those instructions. 

## Video walk through

In this video I demonstrate the installation of Python and Jupyter on the Windows operating system. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/6anwnNyPqgY?si=jHse-HjPu7I1RXhP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## The basic steps

* From [python.org](https://www.python.org/){target="_blank"} download the installer. *Hover your mouse over the main 'Download' button and a button for the current version 3.14.0 should appear, or use this [direct link](https://www.python.org/ftp/python/3.14.0/python-3.14.0-amd64.exe){target="_blank"} to the basic 64-bit installer.*
* Open the downloaded installer and ensure that the tick box to *add python.exe to the PATH* is ticked. Then start the install.
* When the install successfully completes open the windows command prompt and type 
~~~
pip install notebook
~~~
* This command should install the Jupyter notebook server and associated programs. 
* When this completes you can start the Jupyter notebook server by typing the following command into the command prompt
~~~
jupyter notebook
~~~
* After a few moments the Jupyter file browser should open up in your web browser and you are ready to go. 
* In order to use the Sympy library in your notebook you will need to install it first into your Python system. This can be done by opening the Windows command prompt and entering the command
~~~
pip install sympy
~~~

If these steps have been successful you should now have a working set-up that will allow you to work on your coursework just like in the labs. Best practice is to have your working directory under your MMU Onedrive so that everything is backed up, synced up and available to you wherever you are. 



