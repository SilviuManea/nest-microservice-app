# nest-microservice-app
The responsibility of nest-microservice-app is to print “Hello World” in the terminal in response to an event send from the nest-microservice-client

# Objective
Each time when you refresh your browser you can see “Hello World from client!” repeating in the terminal. Because every time when you refresh the browser,message_printed event will be fired from the client and the microservice will get the event over the TCP transport layer and the corresponding code will be executed.

# Commands
1.Launch the microservice app -> cd microservice-app first and then launch it with npm run start
2.Do the same with the microservice-client.
3.Navigate to localhost:3000 and refresh he page. IF everything works fine, with each refresh you will see a hello World console log in the microservice-app terminal. 
