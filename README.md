# Github setup guide

1. download github client for windows here https://central.github.com/deployments/desktop/desktop/latest/win3
2. just do the standard installation, there are lots of questions where for our purposes it does not matter what you choose.
3. After installation test if the install has worked by opening a command ( windows key , then type cmd, then press enter) and then type "git --version". You should see a response "git version 2......"
5. Next step is to clone the folder, for this create a new folder somewhere, enter it and do a right click. There should be an option "Git bash here" - select that
6. In the shell that opened - enter "git clone https://github.com/JanQuarentaydos/jh-eee". It should now copy the content of the URL into the folder
7. Enter git --global user.name "yourname or alias"
8. Enter git --gloabl user.email "your@mail.com"
9. Enter git checkout -b "work-julius"
10. You can now start working with the files.
11. Once you have an amount of changes that is worth saving (best to do it often especially in the beginning) do the right click in the folder -> git bash again and this time enter git commit -m "type here a short statement of the changes you made". You should see a response that tells you how many files you changed
12. If that worked you can type git push. (It may be that there is a message that prompts you to do sth. like this "git push --set-upstream origin work-julius " Copy that command and enter it afterwards the git push command should work.
   With that you're good to go
