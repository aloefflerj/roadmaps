## How does the internet work?

The Internet is a network.

![code-guy-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/d4300ff4-65c4-410c-b133-27578f79f942)
![network](https://github.com/aloefflerj/roadmaps/assets/51006938/9b3c6696-1943-4ae3-b5da-8aa81d3500ee)

But on a global scale.

![code-guy-explaining2](https://github.com/aloefflerj/roadmaps/assets/51006938/b51da748-8b5a-4ff5-bfbb-bbef48ba1de3)
![global-network](https://github.com/aloefflerj/roadmaps/assets/51006938/afae5463-65a6-449c-bf17-38b593bcacb4)

---

It is a network of smaller networks connected by a series of standardized protocols.

![code-guy-explaining3](https://github.com/aloefflerj/roadmaps/assets/51006938/3e1d7f6f-886e-43ba-be67-0642a00700c9)
![sending-file-network](https://github.com/aloefflerj/roadmaps/assets/51006938/d6e888a3-06e7-4aa3-a26a-b936f270fc41)

---

These networks are connected by a complex network of routers and switches.

![code-guy-explaining2](https://github.com/aloefflerj/roadmaps/assets/51006938/b51da748-8b5a-4ff5-bfbb-bbef48ba1de3)
![routers-and-switches](https://github.com/aloefflerj/roadmaps/assets/51006938/c2394c12-93a7-40ca-8824-8c999b365b34)

---

There are undersea cables that form the backbone of the internet. These are fiber optic cables that run deep under the ocean and are used to transmit data between continents.

![code-guy-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/d4300ff4-65c4-410c-b133-27578f79f942)
![seafloor-cable](https://github.com/aloefflerj/roadmaps/assets/51006938/e4a95ca7-5bf6-4c69-8578-c4d17f8842a9)

---

So, let's say you want to access the given website: [https://random.cat/view/500](https://random.cat/view/500).

First, you'll need to use the web browser on your computer. When you enter the URL address you want to access, you make a request to the server. In this case, your web browser is considered the **client**, and the computer that will respond to the request is the **server**.

![code-guy-explaining3](https://github.com/aloefflerj/roadmaps/assets/51006938/3e1d7f6f-886e-43ba-be67-0642a00700c9)
![client-server](https://github.com/aloefflerj/roadmaps/assets/51006938/6c63071f-f946-4cac-ba49-2ae7f87fa33f)

---

Data that is transmitted over the Internet is sent in small pieces called **packets**. These packets are routed to their destination through different network devices (routers or switches). When they reach their destination, the packets are reassembled into the information that was requested.

![code-guy-explaining3](https://github.com/aloefflerj/roadmaps/assets/51006938/3e1d7f6f-886e-43ba-be67-0642a00700c9)
![reassembling-packets](https://github.com/aloefflerj/roadmaps/assets/51006938/e0c851ee-e787-4aa8-8a2f-6db0183619e7)

---

The data being transferred passes through a series of protocols that are organized into layers. The layers of the TCP/IP model are:

- Application layer;
- Transport layer;
- Internet layer;
- Network access layer.

![code-guy-explaining2](https://github.com/aloefflerj/roadmaps/assets/51006938/b51da748-8b5a-4ff5-bfbb-bbef48ba1de3)
![layers](https://github.com/aloefflerj/roadmaps/assets/51006938/bcba1952-1981-4f19-92ec-5a6a31464faa)

---

When you type [https://random.cat/view/500](https://random.cat/view/500), your browser sends a request to the Domain Name System (DNS). The system is like a phone book for the internet. It translates the domain name into an IP address, a unique number that identifies a server on the internet. This is done by the application layer.

![code-guy-explaining3](https://github.com/aloefflerj/roadmaps/assets/51006938/3e1d7f6f-886e-43ba-be67-0642a00700c9)
![dns](https://github.com/aloefflerj/roadmaps/assets/51006938/21ee89b8-1ae4-4b2d-99b4-17d483d36b12)

---

Now that we know the IP, the browser establishes a connection using the TCP/IP protocol. This reliable communication is called a “handshake”.

![code-guy-explaining2](https://github.com/aloefflerj/roadmaps/assets/51006938/b51da748-8b5a-4ff5-bfbb-bbef48ba1de3)
![handshake](https://github.com/aloefflerj/roadmaps/assets/51006938/5ab2a61b-9afd-47a3-9efb-7f0f48cf64ca)

---

Now that we have established reliable communication, the HTTP protocol can fetch resources from the server. HTTP is the basis for all data exchange on the web, and is an application layer protocol that is sent over TCP, or over a TLS-encrypted TCP connection. It is used to fetch documents, images, and videos. It is also used to post content to servers.

The server will now handle your request and send back the content you requested. The data will be sent via packets that will be reassembled on the client side.

![code-guy-explaining3](https://github.com/aloefflerj/roadmaps/assets/51006938/3e1d7f6f-886e-43ba-be67-0642a00700c9)
![reassembling-packets-flipped](https://github.com/aloefflerj/roadmaps/assets/51006938/a3459817-a9d3-44b1-b619-d8afbfeb1ab5)

