ewDirectory
packages.microsoft.gpg
Pictures
Pictures/Waves-1280x720.jpg
Pictures/Rogue-Waves-1280x720.jpg
Pictures/images.jpeg
Pictures/MIT-Rogue-Waves-1280x720.jpg
Pictures/pexels-photo-635279.jpeg
Pictures/funnyface.jpeg
Public
search_result.md
Templates
Videos
workspace
workspace/cohort.md
workspace/excersice.md
workspace/recruits.md
workspace/README.md
workspace/umuzi.md
workspace/summary.md
workspace/CHANGELOG.md
find: ‘.pdf’: No such file or directory
rulani@rulani:~$ find ~ -name \ "*pdf"
find: ‘/home/rulani/.cache/dconf’: Permission denied
find: ‘/home/rulani/.dbus’: Permission denied
rulani@rulani:~$ sudo find ~ -name \ "*pdf"
[sudo] password for rulani:              
rulani@rulani:~$ ls -l
total 48
drwxr-xr-x  3 rulani rulani 4096 Oct 29 14:49 Desktop
drwxr-xr-x  2 rulani rulani 4096 Oct 29 14:50 Documents
drwxr-xr-x 28 rulani rulani 4096 Oct 28 16:08 Downloads
drwxrwxr-x  2 rulani rulani 4096 Oct 29 11:28 helloworld.java
drwxr-xr-x  2 rulani rulani 4096 Oct  7 11:26 Music
drwxrwxr-x  2 rulani rulani 4096 Oct 29 10:25 NewDirectory
-rw-rw-r--  1 rulani rulani  641 Oct  8 09:50 packages.microsoft.gpg
drwxr-xr-x  2 rulani rulani 4096 Oct 15 13:53 Pictures
drwxr-xr-x  2 rulani rulani 4096 Oct  7 11:26 Public
-rw-rw-r--  1 rulani rulani    0 Oct 29 14:46 search_result.md
drwxr-xr-x  2 rulani rulani 4096 Oct  7 11:26 Templates
drwxr-xr-x  2 rulani rulani 4096 Oct  7 11:26 Videos
drwxrwxr-x  2 rulani rulani 4096 Oct 29 14:41 workspace
rulani@rulani:~$ nao --v

Command 'nao' not found, did you mean:

  command 'tao' from deb taopm
  command 'nano' from deb nano
  command 'na6' from deb ipv6toolkit
  command 'nam' from deb nam
  command 'yao' from deb yorick-yao

Try: sudo apt install <deb name>

rulani@rulani:~$ sudo apt install nano
Reading package lists... Done
Building dependency tree      
Reading state information... Done
nano is already the newest version (2.9.3-2).
0 upgraded, 0 newly installed, 0 to remove and 58 not upgraded.
rulani@rulani:~$ nano my bio.md
rulani@rulani:~$ mkdir my_files && mv my_bio.md\
> mkdir my_files && mv my_bio.md
mv: cannot stat 'my_bio.mdmkdir': No such file or directory
rulani@rulani:~$ mkdir my_files && mv my_bio.md
mkdir: cannot create directory ‘my_files’: File exists
rulani@rulani:~$ mv my_bio.md my_files
mv: cannot stat 'my_bio.md': No such file or directory
rulani@rulani:~$ mkdir my_files
mkdir: cannot create directory ‘my_files’: File exists
rulani@rulani:~$ pwd
/home/rulani
rulani@rulani:~$ ls
Desktop          packages.microsoft.gpg
Documents        Pictures
Downloads        Public
helloworld.java  search_result.md
Music            Templates
my_files         Videos
NewDirectory     workspace
rulani@rulani:~$ touch my_bio.md
rulani@rulani:~$ mv my_bio.md > my_files/
bash: my_files/: Is a directory
rulani@rulani:~$ cd my_files/ | tee mv my_bio.md
rulani@rulani:~$ history
    1  sudo apt update
    2  sudo apt install chrome
    3  sudo apt upgrade
    4  sudo apt install node
    5  sudo apt -f upgrade
    6  sudo apt install -f upgrade
    7  sudo lshw
    8  cd
    9  sudo apt-get install qshutdown
   10  pwd
   11  ls
   12  clear
   13  ls
   14  sudo apt install code_1.38.1-1568209190_amd64.deb
   15  sudo apt install ./code_1.38.1-1568209190_amd64.deb
   16  sudo apt update
   17  sudo dpkg --configure -a
   18  sudo apt update
   19  sudo apt upgrade
   20  curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
   21  sudo install -o root -g root -m 644 packages.microsoft.gpg /usr/share/keyrings/
   22  node acc.js
   23  ls
   24  cd Desktop/
   25  cd dev/
   26  ls
   27  node acc.js
   28  node acc.js
   29  sudo apt install nodejs
   30  node acc.js
   31  clear
   32  node acc.js
   33  clear
   34  node acc.js
   35  clear
   36  node acc.js
   37  clezr
   38  clear
   39  node acc.js
   40  - 2
   41  node acc.js
   42  pwd
   43  ls
   44  cd Desktop/dev/
   45  ls
   46  git clone https://github.com/Rpanguana/Bank-Account.git
   47  sudo apt install git
   48  git clone https://github.com/Rpanguana/Bank-Account.git
   49  ls
   50  mv acc.js Bank-Account/
   51  ls
   52  cd Bank-Account/
   53  git add .
   54  git status
   55  git commit -m "acc.js"
   56  git config --global user.email "you@example.com"
   57  git config --global user.email "filipe.panguana@outlook.com"
   58  git config --global user.name "Rpanguana"
   59  git commit -m "acc.js"
   60  git push
   61  git add .
   62  git commit -m "acc.js 01"
   63  git push
   64  vs code
   65  ls
   66  cd Desktop/
   67  cat https://github.com/Rpanguana/jasmine.git
   68  git clone https://github.com/Rpanguana/jasmine.git jasmine
   69  cd dev/
   70  ls
   71  cd Bank-Account/
   72  git add .
   73  git commit -m "last commit of the day"
   74  git push
   75  poweroff
   76  pwd
   77  ls
   78  cd Desktop/
   79  cd dev/
   80  ls
   81  git clone https://github.com/Rpanguana/memory-game-in-vannilla-Js.git memorySlot
   82  ls
   83  cd Desktop/dev/memorySlot/
   84  ls
   85  git add .
   86  git commit -m "adding jasmine standalone"
   87  git push
   88  pwd
   89  git add .
   90  git commit -m "some content"
   91  git push
   92  poweroff
   93  pwd
   94  cd Desktop/
   95  ls
   96  cd dev/memorySlot/
   97  ls
   98  cd jasmine-standalone-3.5.0/
   99  cd src/
  100  cd ../
  101  git add .
  102  git commit -m "added some css and html"
  103  git push
  104  ~
  105  /home
  106  bash ~
  107  poweroff
  108  pwd
  109  cd Desktop/dev/memorySlot/jasmine-standalone-3.5.0/src/
  110  cd ../
  111  git status
  112  git pull
  113  git add .
  114  git commit -m"just a commit'
  115  git commit -m "just a commit"
  116  git push
  117  git pull
  118  ~
  119  cd ../
  120  pwd
  121  git clone https://github.com/Rpanguana/memory-game-in-vannilla-Js.git memoryslot
  122  poweroff
  123  pwd
  124  cd Desktop/dev/memoryslot/
  125  git add .
  126  git commit -m "fixed a display bug in html file"
  127  git push
  128  poweroff
  129  cd Desktop/dev/memoryslot
  130  git add .
  131  git commit "nothing really"
  132  git commit -m "nothing really"
  133  git push
  134  git pull
  135  shutdown now
  136  cd Desktop/dev/
  137  ls
  138  cd Bank-Account/
  139  git pull
  140  git add .
  141  git commit -m "some changes"
  142  git push
  143  ls
  144  cd Desktop/dev/ls
  145  cd Desktop/dev/
  146  ls
  147  Bank-Account/
  148  git add .
  149  ls
  150  cd Bank-Account/
  151  git add .
  152  git commit -m "need to save to backup files"
  153  git push
  154  shutdown now
  155  ping www.google.com
  156  ping www.google.com
  157  ls
  158  ex. "./azureus"
  159  sh "./azureus"
  160  vim azureus
  161  cat azureus
  162  history
  163  ls
  164  pwd
  165  mkdir NewDirectory
  166  mkdir workspace
  167  cd workspace
  168  ls
  169  touch README.md
  170  ls
  171  cp REDME.md CHANGELOG.md
  172  cp README.MD CHANGELOG.MD
  173  cp README.md CHANGELOG.md
  174  touch excersice.md
  175  rm excercise
  176  rm excercise.md
  177  touch excercise.md /tmp
  178  ls
  179  mv exercise /tmp
  180  mv excercise /tmp
  181  mdirk /tmp
  182  mkdir /tmp
  183  mv excercise.md /tmp
  184  ..cd
  185  cd..
  186  .cd
  187  ../
  188  ./
  189  cd /tmp
  190  ls
  191  cd workspace
  192  cd ..
  193  rm /tmp/excercise.md
  194  touch umuzi.md recruit.md cohort.md
  195  sudo touch umuzi.md recruit.md cohorts.md
  196  cat > umuzi.md
  197  cd ~/workspace/
  198  ls
  199  touch umuzi.md recruits.md cohort.md
  200  cat > umuzi.md
  201  cat umuzi.md
  202  cat > recruits.md
  203  cat > cohort.md
  204  cat cohort.md recruits.md umuzi.md
  205  cat recruits.md umuzi.md cohort.md summary.md
  206  sudo apt install openjdk-11-jdk
  207  mkdir helloworld.java
  208  ls | grep helloworld
  209  javac helloworld.java
  210  ls | grep helloworld
  211  java helloworld
  212  sudo snap install intellij-idea-community --classic
  213  sudo apt install intellij-idea-community --classic
  214  sudo apt install intellij-idea-community
  215  cd workspace
  216  ls
  217  cat umuzi.md recruit.md cohort.md >summary.md
  218  ls
  219  cat umuzi.md recruits.md cohort.md >summary.md
  220  cat >>summary.md
  221  locate umuzi
  222  ls
  223  cd ..
  224  locate umuzi
  225  locate umuzi > search_result.md
  226  cd workspace
  227  cd ..
  228  cd Documents
  229  touch pad.md
  230  cd desktop
  231  cd ..
  232  cd Desktop
  233  mkdir Work
  234  cd ..
  235  cd Documents/
  236  cp pad.md pad_copy.md
  237  locate updatedb
  238  cd .
  239  cd ..
  240  locate pad_copy.md
  241  cd -1
  242  locate* pdf
  243  find ~ -name\*.pdf
  244  find * .pdf
  245  find ~ -name \ "*pdf"
  246  sudo find ~ -name \ "*pdf"
  247  ls -l
  248  nao --v
  249  sudo apt install nano
  250  nano my bio.md
  251  mkdir my_files && mv my_bio.mdmkdir my_files && mv my_bio.md
  252  mkdir my_files && mv my_bio.md
  253  mv my_bio.md my_files
  254  mkdir my_files
  255  pwd
  256  ls
  257  touch my_bio.md
  258  mv my_bio.md > my_files/
  259  cd my_files/ | tee mv my_bio.md
  260  history
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ ^C
rulani@rulani:~$ 

	
	
	

