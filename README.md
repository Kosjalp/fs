# fs
This was made for macOS.
**How to use:** </br>
1. One time use: </br>
   Go to terminal and type zsh [File path]</br>
2. Set as command</br>
Step 1: Go to /usr/local/bin</br>
Step 2: Move fs.sh there</br>
Step 3: Take ownership of file to edit it OR you can use an editor within the terminal for slight added security, however to run it you must sudo fs. (To take ownership: sudo chown $(whoami) /usr/local/bin/fs.sh or if you don't trust this look it up)</br>
Step 4: Rename fs.sh to fs</br>
Step 5: do chmod +x /usr/local/bin/fs</br>
Now you should just be able to type fs in a new terminal window, put in your password for sudo, and you are done.</br>
This will loop until your sudo session stops, to prevent that you can do a set of commands that you can look up on google.</br>

**_WARNING: THIS WILL LOOP UNTIL MANUALLY STOPPED. THIS CAN CONSUME A LOT OF RAM AS TERMINAL HISTORY FILLS UP._**</br>
</br>
This can be used to stress test your system or something </br>
You can set the maximum amount of lines saved in RAM in _terminal settings > profiles > window > scrollback_ if you want to use this for asthetics.

_Fun fact: fs stands for file scroll._
