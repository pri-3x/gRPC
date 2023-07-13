# gRPC

![Screenshot (48)](https://github.com/pri-3x/gRPC/assets/53579127/4704ab1b-a3e3-43b0-b494-e8640416ff85)


In gRPC, there are four types of streaming supported:

1) Unary RPC:

In unary RPC, the client sends a single request to the server and receives a single response in return.
It is similar to a traditional remote procedure call (RPC) where the client waits for the server to process the request and send back the response.

2) Server-side Streaming RPC:

In server-side streaming RPC, the client sends a single request to the server, and the server responds with a stream of multiple messages.
The client sends the request using a method call and receives a stream of responses from the server.

3) Client-side Streaming RPC:

In client-side streaming RPC, the client sends a stream of multiple messages to the server and waits for a single response.

4) Bidirectional Streaming RPC:

In bidirectional streaming RPC, both the client and the server can send and receive streams of messages simultaneously.
The client and the server establish a stream connection, and both can send multiple messages independently.
This allows for real-time communication and interaction between the client and the server.



