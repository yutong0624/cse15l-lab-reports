**1. Installing VScode**

Download and install the app, Visual Studio Code from this website [Link]([http://a.com](https://code.visualstudio.com/)). I skipped this process because I alreday had it installed.
It should be like this (example of mac):
![Image](sc1)


**2. Remotely Connecting**
If you are using Windows, go to the website: [Link](https://gitforwindows.org/) to download and install the git. Follow the instruction on this link: [Link](https://stackoverflow.com/a/50527994) to set git bash as the default terminal in Visual Studio Code. I skipped this step because I use Mac

Then, to connect to ssh, open a new terminal in VScode (Ctrl or Command + `, or use the Terminal → New Terminal menu option). Then type ssh followed by a space and your course specific account. It should look like this: 
```
$ ssh cs15lwi23zz@ieng6.ucsd.edu
```
but with different account.

If you are new to this server, a image like this will show:
```
ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
Type ```yes``` in the terminal, and then input your password as instruction. It should be like this once you log in:
![Image](Screenshot2)
You are now connected to ssh and link to the computer in CSE basement.


**3.Trying Some Commands**
Run the commands ```cd```, ```ls```, ```pwd```, ```mkdir```, and ```cp``` a few times in different ways, and see what they do. What commands will cause an error and why?

