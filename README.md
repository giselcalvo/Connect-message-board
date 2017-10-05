Connect-message-board

Running application


terminal 1
Start mongodb
sudo mongod

terminal 2
start nodemon
cd message-board
nodemon

terminal 3
building the angular application
cd message-board/public
ng build -w

browser
go to localhost:8000
