## How does the internet work?

So, what happens when I access a web page? How does my computer knows where that page is? How does the content is shown in my web browser almost instantly?

Let's try this page: [https://random.cat/view/500](https://random.cat/view/500).

1. I open my web browser and fill in the address bar with the website address;
2. My web browser takes that information and sends a message through a series of protocols, known as:
    - Application Layer (HTTP(S) protocol);
    - Transport Layer (TCP protocol);
    - Network Layer (IP protocol);
    - Link Layer (IEEE 802 (WiFi))
3. _The application layer_ performs a _DNS_ lookup. The _DNS_ (Domain Name System) associates domain names to an _ip_ address. So, if I type [http://www.pudim.com.br](http://www.pudim.com.br) it will search for its _ip_. The application layer also will add a _port_ number to the _ip_, a number assigned to direct data to a specific service on the machine. HTTP is usually assigned to port `80` and HTTPS to port `443`.

![code-explaining](https://github.com/aloefflerj/roadmaps/assets/51006938/3418ba9e-7882-46a1-99ad-446a5368c5be)

---

<details>
    <summary>Details</summary>
    https://roadmap.sh/guides/what-is-internet
</details>
![networkx4](https://github.com/aloefflerj/roadmaps/assets/51006938/103974cb-619f-43f0-9518-7b9092619a29)
