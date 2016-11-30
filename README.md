
# nodejschatroomdemo

```
This is a demo for angularjs/socket.io/nodejs/express/mongodb online chatroom which includes:

* Enter user name into chatroom
* Multiple user chat at the same time
* Display connected user
* User enter/leave notification
* Send message with user name
* save messages into Mongodb
```

### Prerequisites

What things you need to install the software and how to install them

```
* Download and install node.js from https://nodejs.org/en/

```

## Getting Started

```
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.
```

### Installing

```
1. git clone https://github.com/DaJiangCK/nodejschatroomdemo.git
2. cd daschatroom
3. npm install
4. npm start
```

## Live example

```
https://daschatroom.herokuapp.com/
```

## Note

you can see the commented codes in server/index.js which work for mongodb

```javascript
// var mongoose = require('mongoose');
// var Message = mongoose.model('Message', {
// 	name: String,
// 	msg: String
// });

//Connection
// mongoose.connect("mongodb://localhost:27017/test", function (err, db) {
//     if (!err) {
//         console.log("we are connected to mongo");
//     }
// })

// var message = new Message(sockectObj);
// message.save();
```
