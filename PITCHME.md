@title[Splash Page]
### Optimizing Development Workflow and Tooling
![splash image](imgs/splash.png)

Help your future self!
+++

### What is your Workflow/Tooling
* Tools, Applications and Process that assist in code development

Note:
Think of the collection of: Tools, Applications and Process that you use to complete tasks 

+++ 

### Why should you Optimize your Workflow/Tooling
* Easier to integrate the use of new technologies
* Process of code development becomes easier/faster
* be prepared for the next "Big Thing" in software development 

Note: 
1 when your tools and workflow is Optimize using new technologies is easier

2 try to automate things we do daily (I have an example)

3 We should always be looking were the puck is going (not where the puck is)

+++
 ### Recommendations on how to Optimize your Workflow and Tooling 
 *  Try to identify parts of your "workflow" that could be optimized
 *  Can this part of the Workflow or tool be automated
 *  Investigate new features, plugins, add-ons in currently used apps  
 *  Search for alternative app that meets your needs

Note:
Here are a few broad recommendations  

---
## Examples

Note:
These are just a few examples, there are many more examples that I will not touch on

I want to stress that this part is more of a FYI these examples exist than I use an app over another

Have the mind set with  these example  of could help instead of should help 
---

### File Manipulation

Note:
File editing and saving

+++
### Q/A
* What Applications are you using to manipulate files  
* Why do you use this Application
* What do you like about this Application
* What do you dislike about this Application

+++ 
### Vi(m)
![gif](gifs/file-editing-vi.gif)
+++
![gif](https://github.com/scrooloose/nerdtree/raw/master/screenshot.png)
 <a href="https://vimawesome.com/" target="_blank">Vimawesome Plugins</a>
 
+++
### Notepad++
![gif](gifs/file-editing-np-pp.gif)
<a href="http://docs.notepad-plus-plus.org/index.php/Plugin_Central" target="_blank">Notepad++ Plugins</a>     
+++
### VSCODE
![gif](gifs/file-editing-vscode.gif)
+++
![gif](imgs/vscode/vscode-git-feature.PNG)
---

### Linting
![gif](imgs/linting/explain-code-linting.jpg)
+++
### Q/A
* What Applications are you using to lint files  
* Why do you use this Application
* What do you like about this Application
* What do you dislike about this Application
+++
###  
![gif](imgs/linting/js-linting-ex.png) 
+++
![gif](imgs/linting/linting.gif)     
+++
![gif](imgs/linting/perl-vscode-linting.gif)
---

### Navigation/Presentation 
+++
### Q/A
* What do you look for in Navigation/Presentation in Applications
* How do you configure Applications

+++ 
### Theming
+++
### Vim
![gif](imgs/vim/vim-theme.png)
+++
![gif](imgs/vim/vim-theme-1.png) 
+++
![gif](imgs/vim/vim-theme-2.jpg)
+++
### Notepadd ++ 
![gif](imgs/notepadd++/notepad-plus-plus-theme-2.JPG)
+++
![gif](imgs/notepadd++/notepad-plus-plus-theme-1.png)
+++
![gif](imgs/notepadd++/notepad-plus-plus-theme.png)
+++
### Vscode 
![gif](imgs/vscode/theme1.png)
+++
![gif](imgs/vscode/themes-ayu.gif)
+++
![gif](imgs/vscode/icons.png)
+++
### Navigation
![gif](imgs/acsdev-nav.gif) 
+++
![gif](gifs/nav-pres-1.gif)

---

### Remote Procedures

Note:
Doing something remotely

+++
### Q/A
* What Applications are you using to do Remote Procedures
* Why do you use this Application
* What do you like about this Application
* What do you dislike about this Application

+++
### SSH
![gif](gifs/acsdev-ssh.gif)    
+++
### SFTP 
![gif](gifs/notepad-sftp.gif)

+++
Docker ?
![gif](gifs/eas-docker-run.gif)
---

### Software Management

Note: Managing the software that you use 
+++
### Q/A
* What Applications are you using to do software management
* Why do you use this Application
* What do you like about this Application
* What do you dislike about this Application

+++
### Package manager
![gif](gifs/linux-pkmag.gif) 
+++
### Git

```git clone <tool>```
Note: 

git clone 
+++
### Binary/Installer 
![mysql-installer](https://docs.oracle.com/cd/E17952_01/mysql-5.0-en/images/mysql-es-win32-fig1.png)
+++
### Docker
```docker run <tool>```

Note:
docker run -d -p 9000:9000 --restart always -v /var/run/docker.sock:/var/run/docker.sock -v /opt/portainer:/data portainer/portainer

---
### A few Optimizations I made

- Bitbucket search   -> ripgrep
- Docker for windows -> Docker + VM |
- Notepadd ++        -> Vscode |
- MobaXterm          -> cmder/ linux term |
- Powerline-shell |

---

### Tying it Altogether
 
  #### Case :  When I write perl code I want to automatically lint (perltidy / perlcritic) the file(s) I was editing
  - first phase  : Create a git pre-commit hook that automatically perltidy and perlcritic when I commit code 
  - second phase : Run perltidy and perlcritic in a container like what is setup in bamboo |
  - Third phase  : Replace hook with a text editor plugin that runs a container( perltidy and perlcritic) on saved |
  
Note:
 
Here is an example of use parts of the pervious examples and applying them to make my life eaiser
 
---

### Final Thoughts
* Does your "workflow" meet my current your needs ?
* What applications/process need to change 
* How to adapt your current "workflow" to meet your future needs
* Researching new apps/process that make your "workflow" easier
* Browse reddit/github for new and cool apps that could be added to workflow

Note:
optimizing does not stop here with these examples it could be expanded to:

The way we program 

using libaraies to things 
