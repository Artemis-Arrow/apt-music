# apt-music
#installation

run the following commands
```
sudo apt install python3 pip3 git
pip install playsound
git clone https://github.com/Artemis-Arrow/apt-music.git
cd apt-music
```
now open the apt-music file in your favorite text editor, and on line 4 set the variable to ether the file path or the url of the sound you want to play, for example set line 4 to
```
sound = "https://www.youtube.com/watch?v=dQw4w9WgXcQ"
```
now save the file, exit the text editor, and run the following
```
chmod +x apt-music
sudo cp apt-music /bin
```
and finally open your .bashrc or .zshrc or whatever shell you use and add the following line to the aliases 
```
alias apt='apt-music'
```
