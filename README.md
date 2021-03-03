<p align="center" style="text-align:center;">CODA™ Learn To Bash Anything</p>
<p align="center" style="text-align:center;">\m/</p>
<p align="center" style="text-align:center;">
    <img alt="CODA Logo" src="images/CODAlogo.png" width="500" />
</p>


The CODA™ Network presents you with an easy-to-follow series on how to code in bash.


Key Features Include:

  - Create your own bash commands, executable from any directory just like any regular Linux command (ex: cd, ls).

  - Automate any task using scripting. Eliminate the need to do repetitive/boring tasks.

  - Solve problems to difficult answers. Learn to map & simulate a situation for the purposes of making predictions.

  - Program entire processes that include changing directories, manipulating files, and using multiple software's.

  - Have fun :) You are given real life example scripts for automating an entire hack operation via Linux.

  - Feel the power!! The course features real automation scripts for you to practice and use on your daily Linux.

  - It's so easy; simply try typing the scripts out - starting at a level you're comfortable with...

  - The difficulty of the scripts advance very slowly so it's difficult to miss a thing.

  - Good for all skill levels as the scripts begin easy and slowly progress towards expert-level scripting.

  - Each script is filled with comments to help guide you in case you get lost!!

  - Author's email is available in each file. Feel free to ask questions directly, they will generally respond within 24 hrs.


Requirements:

  - A Linux environment.
  
  - A passion to learn!
  
  - Common sense...



ADDITIONAL NOTES
===
How to set up ubiquitous executables (bash-script -> linux command) for your linux environment
Last Updated: 03/03/2021

Use this COMMAND to add a directory to the Linux PATH Environment Variable:

=> PATH=$PATH:~/[folder-containing-bash-file]
	
Where ~/ = home/kali OR ~/home/kali

It's advised that you create a 'bin' folder in your home/[user] directory to store all you bash scripts; for example:

=> cd home/kali
=> mkdir bin
=> PATH=$PATH:~/bin

IMPORTANT: Don't forget to fix any of your bash scripts containing directories or produciung files,
that is, in the case where you want a file output in the same directory the bash command is run; for example:

#!/bin/bash
echo $1 >> ~/bash@pluralsight/1-First-Script/notes.txt

BECOMES...

#!/bin/bash
echo $1 >> ./notes.txt

OR

#!/bin/bash
echo $1 >> notes.txt


If done correctly, you should be able to execute your bash script from any driectory simply using the command name; for example:

=> [name-of-bash-script]

Note: You don't need to specify the '.sh' bash file extension, just put the name!


<p>-------------------------------------------------------------------------------------------</p>
<p>This file was produced by chorononzon@protonmail.ch in association with <strong>The CODA™ Network</strong>.</p>
<p>-------------------------------------------------------------------------------------------</p>

<p align="right" style="text-align:right;"><em>“A man can be himself only so long as he is alone; and if he does not love solitude, 
 he will not love freedom; for it is only when he is alone that he is really free.”
 ― Arthur Schopenhauer</em></p>
