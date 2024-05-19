# tt-duskconfig
tintin++ sample config for main.tin for multi-logging in the multi-user-dungeon(MUD) Blood Dusk. 


Description
------------
It's what it says on the tin.  It's a file to setup auto-login and helpful alias' and triggers for playing the game with two accounts at the same time.  If you've not yet created your account(s), do so. You're permitted up to two accounts per person. 
I have multiple accounts, and so the sample reflects that by separating sessions by #bd1 and #bd2.  This is what I hope is a pretty solid baseline.

Scope: Intended for people brand new to Dusk and MUDs as a whole. 
------------
You can play the game without a client, however using a client will make things infinitely easier than managing two separate windows of a plain old terminal emulator such as putty, bash, putty, etc.   

The playerbase is not as healthy as it once was, so this unfortunately necessitates occasionally running multiple characters at once, when historically there used to be dozens of players on at any time and multi-logging wasn't allowed.  
in v8 this ban was lifted to permit 2 or 3 people to actually do the higher level runs/quests, without assistence of what used to require 4 to 8 people depending on builds.

If you don't already have tintin++ or the windows counter-part WinTin++, you will find tt++ in your Linux distro's repository, and on windows from this website:https://tintin.mudhalla.net/download.php
the installer version is the best way to go for windows.  By default it'll try to install in the user's folder, I recommend you change it to something else like 'C:\WinTin++\' so that it's easy to find.


I may add an account creation file later for the noobs, but it's pretty straight forward. the instructions for that will be basically the same for the auto-login file.  just in case here's what i'm hoping the directions will be:

1.  Download file "newbie"
2.  copy file "newbie" to ~WinTin++\bin.
3.  edit file "newbie" using your preferred text editor with desired account name and password.
4.  Save the file.
5.  launch WinTin
6.  issue the command '#read newbie' (I intend this to be a separate creation session name)
7.  From here it'll have you create your very first character. dump everything into physical save for 2 points into intelligence.  This will be your main fighter. 
These stats set you up pretty well for berserker, taoken, brawler, staffer or gladiator which are all perfectly fine starting careers.
8.  quit out of the session completely by typing quit twice
9.  repeat step 3, 6, and 7 for making a second account with a different username and password.
10.  Once you have completed creating the second account and first character for that account, repeat step 8
11. close Wintin 
12. continue to setting up main.tin as outlined below.

______________________________

The Autologin config:

Method 1:
1. Download sample_main.tin
2. Delete main.tin from the ~WinTin++\bin folder
3. Rename it from sample_main.tin to main.tin.
4. move it to the ~WinTin++\bin folder.
5. open the new main.tin file in your text editor and replace the <account> and <password> fields with your account names and passwords 
6. Save It
7 launch Wintin.

Alternatively you can just: 

1. Download sample_main.tin
2. Open it.
3. Copy and paste it's contents into the empty main.tin file WinTin comes with.
4. Replace the <account> and <password> fields with your account names and passwords.
5. Then save it.  
6. Launch the client.

I'm not your mother, either and method works. 

 Hope to see you soon!  
  - Jonan/Shyanna