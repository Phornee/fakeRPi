# fakeRPi

This riculous but useful fake module, can be used if you want to create and debug Raspberry Pi code in your PC.
Debugging and editing in a PC is much more comfortable that in the Pi, (much more if you are using a Pi headless).
I hate nano, i love Pycharm. I want to be able to debug the logic of my programs in the PC with Pycharm, assuming that 
for example all the GPIO stuff will be ignored BUT (and here it comes the magic) without needing to change any code to 
make the program run in the PC.

So, you can clone this project in your workspace, naming the folder as RPi, and thats all....
1) You can debug your program in Pycharm in your PC without changing a single line
2) After you are happy with your changes, you can just commit and push
3) Then you can just pull from your Raspberry Pi... and there you go!

Of course.... no need to say that the inexisting GPIO pins of you PC, won´t work at all ;)