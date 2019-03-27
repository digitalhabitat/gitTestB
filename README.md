###this is a test please ignore
##test
#test

## This is will be extremly disorganize at first

testing out draw.io github integration
<a href="http://digitalhabitat.github.io/gitTestB/.html" target="hardware_system_diagram.html">self-editing.html</a> is a HTML file with embedded diagrams. The file uses nanocms.js for GitHub I/O and diagram editing, and Bootstrap and nanocms.css for some fancy CSS styles. HTML is used as a container for mutiple diagrams in different formats, including inline SVG with links.


Getting started with git from command line

make working directory into a Git repository

```sh
git init
```
or if you have a specific directory in mind

```sh
git int <directory>
```

if you forgot your ssh password you will need to make generate a new key
```sh
ssh-keygen -t rsa -C "youremail@whatever.com"
```
Press enter to save key in default location
Enter y to overwrite existing id_rsa file
Enter a password you won't forget this time

copy contents from id_rsa.pub and add to github shh key in settings

add you newly generated ssh key to the ssh-agent
```sh
ssh-add ~/.ssh/id_rsa
```

to test 
```sh
ssh -T git@github.com
```


