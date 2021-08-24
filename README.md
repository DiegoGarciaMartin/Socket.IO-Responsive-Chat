[![CI](https://github.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/actions/workflows/main.yml/badge.svg)](https://github.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/actions/workflows/main.yml)

# Socket.IO Responsive Chat

An implementation of a responsive chat with NodeJS and Socket.IO.

### Screenshots
<hr>

#### Computer screen

<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_01.png">

<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_07.png">

<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_08.png">

<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_11.png">

<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_12.png">

#### Mobile screen

<table>
	<tr>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_02.png">
		</td>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_03.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_04.png">
		</td>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_05.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_06.png">
		</td>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_09.png">
		</td>
	</tr>
	<tr>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_10.png">
		</td>
		<td>
			<img height="400px;" src="https://raw.githubusercontent.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat/master/screenshots/Screenshot_SocketIO%20Chat_13.png">
		</td>
	</tr>
<table>

### Prerequisites
<hr>

<ul>
	<li>
		NodeJS v6.1.0+
	</li>
</ul>
	

### How to run
<hr>

<div>
	<ul>
		<li>
			<span>Clone repository</span><br>
			<span>> git clone https://github.com/DiegoGarciaMartin/Socket.IO-Responsive-Chat</span>
		</li>
		<li>
			<span style="font-weight: bold;">Enter the directory</span><br>
			<span>> cd Socket.IO-Responsive-Chat/src</span>
		</li>
		<li>
			<span style="font-weight: bold;">Install dependencies</span><br>
			<span>> npm install</span>
		</li>
		<li>
			<span style="font-weight: bold;">Execute app</span><br>
			<span>> npm start</span>
		</li>
	</ul>

</div>

It is very important use the npm to start the app, because the scripts of npm generates files minified of css and javascript.

And point your browser to http://localhost:5555


### Test
<hr>

Tests performed with <a href="https://mochajs.org/">Mocha</a>

To run test, execute the app in one terminal: npm start

In other terminar, execute the tests: npm test

### Features
<hr>

<ul>
	<li>
		It supports multiple rooms and private chats between users.
	</li>
	<li>
		The users can join to the chat after entering a unique username on website load.
	</li>
	<li>
		The rooms supports multiples users at the same time. By default, only three rooms are created of example.
	</li>
	<li>
		A notification is sent to all users when a user joins or leaves the chat.
	</li>
	<li>
		Responsive web design.
	</li>
</ul>


### License
<hr>

GNU GENERAL PUBLIC LICENSE V3
