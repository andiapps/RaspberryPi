# How To Start

1.	<b>Node Environment</b></br>
	curl -sL https://deb.nodesource.com/setup_5.x | sudo bash -</br>
	sudo apt-get install -y nodejs

2.	<b>Install Module</b>
	*	npm install bleno
	*	npm install --save datauri
	* 	npm install raspicam
	* 	npm install rpi-gpio

3.	<b>Run</b></br>
	sudo node main.js

4.      Once the server is up and running the iOS app will be able to discover the player's raspberry pi via bluetooth. 

# First version known problems [Please help!]

1. The combination of this server side code works well if the raspberry pi connects the motor using L298N motor driver board but it will totally have a problem if player's Pi RC car uses Explorer HAT pro as motor control board. I think the problem is in the GPIO ports (I am very new to Pi and its accessory boards' GPIO). 
2. I have no idea how to realize feature of changing speed which the player can use to perform the action of 'speed up' when they are racing with each other. It would be fine if this app work will only be used as AR tank battle but certainly being a problem if it also has to serve the purpose of AR car racing. So far I have the idea of changing the board's output power but I haven't find out exactly how. 



