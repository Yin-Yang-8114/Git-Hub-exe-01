GitHub exe:
1) mkdir pixel-quest ; cd pixel-quest
2) echo "Game project ready" >> game.txt
3) git init 
4) git add . ; git commit -m "first commit"
5) i created a GitHub repository named GitHub exe 01
6) now i will link that to my git local repo by executing <git remote add origin https://github.com/Yin-Yang-8114/GiT-Hub-exe-01.git> to link them.
7) git push --set-upstream origin main
8) cd .. ; mkdir "test cloening" ;cd test cloaning 
9) git clone https://github.com/Yin-Yang-8114/GiT-Hub-exe-01.git
10) ls 
11) cd GIt something...
12) cat game.txt
13)  git switch -c feature/player-menu
14) echo "Player menu started" >> player-menu.txt
15) git add player-menu.txt ; git commit -m "added pleyer menu"
16)  git push --set-upstream origin feature/player-menu
17) cd ../../pixel-quest
18) git pull origin feature/player-menu
19) in GitHub im edited the game.txt file and added now' and comit it with a note in main branch
20) git pull origin main
21) cat game.txt
22) git switch feature/player-menu
23) vim player-menu.txt and added "with Start Game, Settings, and Exit buttons"
24) git add player-menu.txt ; git commit -m "edited player menu" player-menu.txt
25) git push
26) i merged through GitHub feature into main 
27) git switch main ; git pull 
28) ls 
29) echo "difficulty=normal" >> settings.txt
30) git add settings.txt ; git commit -m "adding setting option" settings.txt
31) added setting file on GitHub with difficulty=hard
32) git pull on local
33) vim setting difficulty=balanced
34) git add settings.txt ; git commit -m "fixed setting conflict to balanced"
35) git push 
