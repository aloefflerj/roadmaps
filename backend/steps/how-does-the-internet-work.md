## How does the internet work?

The Internet is a global network of computers.

![code-guy-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/d4300ff4-65c4-410c-b133-27578f79f942)
![network](https://github.com/aloefflerj/roadmaps/assets/51006938/9b3c6696-1943-4ae3-b5da-8aa81d3500ee)

It is a network of smaller networks connected by a series of standardized protocols.

![code-guy-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/d4300ff4-65c4-410c-b133-27578f79f942)
![sending-file-network](https://github.com/aloefflerj/roadmaps/assets/51006938/d6e888a3-06e7-4aa3-a26a-b936f270fc41)

These networks are connected by a complex network of routers and switches.

![code-guy-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/d4300ff4-65c4-410c-b133-27578f79f942)
![routers-and-switches](https://github.com/aloefflerj/roadmaps/assets/51006938/c2394c12-93a7-40ca-8824-8c999b365b34)

There are undersea cables that form the backbone of the internet. These are fiber optic cables that run deep under the ocean and are used to transmit data between continents.

[*cables on the ocean floor*]

So, let's say you want to access the given website: https://random.cat/view/500.

First, you'll need to use the web browser on your computer. When you enter the URL address you want to access, you make a request to the server. In this case, your web browser is considered the **client**, and the computer that will respond to the request is the **server**.

[*accessing the website and server responding]*

Data that is transmitted over the Internet is sent in small pieces called **packets**. These packets are routed to their destination through different network devices (routers or switches). When they reach their destination, the packets are reassembled into the information that was requested.

[*data flowing and reassembling at the user’s end*]

The data being transferred passes through a series of protocols that are organized into layers. The layers of the TCP/IP model are:

- Application layer;
- Transport layer;
- Internet layer;
- Network access layer.

[*layers*]

When you type https://random.cat/view/500, your browser sends a request to the Domain Name System (DNS). The system is like a phone book for the internet. It translates the domain name into an IP address, a unique number that identifies a server on the internet. This is done by the application layer.

[domain being transformed into ip]

Now that we know the IP, the browser establishes a connection using the TCP/IP protocol. This reliable communication is called a “handshake”.

[handshake tcp/ip]

Now that we have established reliable communication, the HTTP protocol can fetch resources from the server. HTTP is the basis for all data exchange on the web, and is an application layer protocol that is sent over TCP, or over a TLS-encrypted TCP connection. It is used to fetch documents, images, and videos. It is also used to post content to servers.

[http fetching data from the server]

The server will now handle your request and send back the content you requested. The data will be sent via packets that will be reassembled on the client side.

[reassambling data into the cat image]
