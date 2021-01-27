# The Internet

The article will explain
- How does the internet work?
- What is the web?
- What is HTTP/HTTPS?
- DNS and how it works?
- What is Domain Name?
- Browsers and how they work?

When you type a web address into your web browser
1. The browser goes to the DNS server, and finds the real address of the server that website lives on
2. The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client over HTTP
3. If the server approves the client's request, the server sends the client "200 OK" message, and then starts sending the website's files to the browser as a series of packets data
4. The browser assembles the small chunks into a complete web page and siplays it to you 

## The internet

TCP/IP (transmission control protocol and internet protocol) are communication protocols that define how data should travel across the internet.
- TCP: 解决数据包送不到的问题
- IP: 解决数据包传不远的问题

## The web - a application based-on the internet

`Clients <- HTTP (request/reponse) -> Servers`

- Clients: web browsers, such as chrome, firefox, safari
- Servers: computers that store webpages, sites or apps

When a client device wants to access a webapge, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

## Domain name & DNS

```
shulun@laptop-work-shulun ~ % dig google.com
; <<>> DiG 9.10.6 <<>> google.com
;; global options: +cmd
;; Got answer:
;; ->>HEADER<<- opcode: QUERY, status: NOERROR, id: 26651
;; flags: qr rd ra; QUERY: 1, ANSWER: 1, AUTHORITY: 0, ADDITIONAL: 1

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 4096
;; QUESTION SECTION:
;google.com.                    IN      A

;; ANSWER SECTION:
google.com.             377     IN      A       172.217.160.78

;; Query time: 54 msec
;; SERVER: 172.20.10.1#53(172.20.10.1)
;; WHEN: Mon Jan 25 08:45:25 CST 2021
;; MSG SIZE  rcvd: 55
```

`google.com` is not the real address of the server. The actual address is `172.217.160.78`. So, Domain Name is used to make ip address more readable.

How is `google.com` translated into `172.217.160.78`? DNS (Domain Name Servers)

DNS are like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's real address before it can retrieve the website using HTTP protocol.

## HTTP/HTTPS

HTTP (HyperText Transfer Protocol) is an application protocol that defines a language for clients and servers to speak to each other.

## Browsers and how they work?

Mainstream browsers' distro
- Chromium,   Blink (WebKit on iOS), V8 JavaScript engine
- Safari,     WebKit, JavaScriptCore
- Firefox,    Gecko, SpiderMonkey
- IE,         Trident, Chakra
- Edge (early) EdgeHTML
