Data packets are able to find the destination without the use of a dedicated channel. Reduces lost data packets

No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted.

You can use the same socket for whatever you want, as long as your protocol handles it.

Observer Pattern: is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

Listener:function in a computer program that waits for an event to occur.

**Event Handler:** code that will run when an event fires(functions)
**Event Driven Programming:** a programming paradigm in which the flow of the program is determined by events
**Event Loop:** construct or design pattern that waits for and dispatches events or messages in a program
**Event Queue:** a repository where events from an application are held prior to being processed by a receiving program or system.
**Call Stack:** is a stack data structure that stores information about the active subroutines of a computer program
**Emit/Raise/Trigger:** an event, which causes all callbacks registered to the event to ‘fire’
**database:** an organized collection of structured information, or data, typically stored electronically in a computer system.

The WebSocket protocol enables interaction between a web browser (or other client application) and a web server with lower overhead than half-duplex alternatives such as HTTP
facilitating real-time data transfer from and to the server.

Client-Side: it is the library that runs inside the browser
Server Side: It is the library for Node.js

WebSocket helps in real-time communication between the Client and the webserver.

This protocol helps in transforming to cross-platform in a real-time world between the server and the client.
This also enables the business worldwide for a real-time web application to enhance and increase the feasibility.
The major advantage it stands over an HTTP connection that it provides full-duplex communication.

**WebSocket**
- provides full-duplex communication, which helps in persisting the connection established between the Client and the Web Server.
- also lives up to the standards and provides the accuracy and efficiency stream events to and from with negligible latency. WebSocket removes the overhead and reduce complexity.
- makes real-time communication effortless and efficient.

**Socket.IO**
- helps in broadcasting to multiple sockets at a time and handles the connection transparently.
- works on all platform, server or device, ensuring equality, reliability, and speed.
- automatically upgrades the requirement to WebSocket if needed.
- is a custom real-time transport protocol implementation on top of other protocols.
- requires both libraries to be used Client side as well as a server-side library.
IO works on work-based events. There are some Client based reserved events like Connect, connect- error, connect-timeout and Reconnect etc.
