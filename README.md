# Data Science Tools - Coursera Project

Template README markdown from [PurplBooth](https://gist.github.com/PurpleBooth)

This project represents the Course project for coursera/data science tools on S. Eannuzzi's Windows 10 desktop and encourage me to 
take better notes :)

## Getting Started

These instructions augment the notes from class, not replace them.

### Prerequisites

See class notes.

### Installing
[gitbash]: https://github.com/seannuzzi/datasciencecoursera/gitbash.PNG "git BASH shortcut"

A step by step series of examples that tell you have to get a development env running that were special to my environment
1. Installed [Microsoft R](https://mran.microsoft.com/open/) instead of the open source R.  Multi-threaded support is needed for my other projects.
  * I was burned by corporate policy around 8.3 filenames.  Fixed by installing R into a directory that did not have spaces in it.  For example: `D:\r\3.3.2`
1. Changed git Bash short up to remove cd to HOME and set start in to appropriate directory
![shortcut][gitbash]
1. Turned off SSL verify to deal with corporate SSL termination by `git config http.sslVerify false`

## Running the tests

What were some of the things I did to test?
1. Basically, the ability to push updates.  I used the notes provided by GitHub after you created a new repository.  
1. Struggled with Corporate networks with SSL and SSH. Solved by pushing updates when NOT on the Corporate network.


## Built With

* Notepad++
* [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Snippet](https://support.microsoft.com/en-us/help/13776/windows-use-snipping-tool-to-capture-screenshots)

0
