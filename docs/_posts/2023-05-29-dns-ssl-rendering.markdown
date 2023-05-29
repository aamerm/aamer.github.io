---
layout: post
title:  "What happens when you type a URL in the browser and press enter?"
date:   2023-05-29 22:15:35 +0530
categories: dns ssl
---
In this post, we will go through all the necessary steps right from the moment an url is typed to the browser to the moment the page is rendered on the browser.
Steps:
* DNS lookup
* SSL handshake
* HTTP request
* HTTP response
* Page rendering

Internet is just loads of computers physically connected together with wires that run under the sea.
Each computer has a unique IP address. IP address is a 32 bit number.
IP address is divided into 4 parts, each part is called an octet.
Each octet is represented in decimal form.

The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like nytimes.com or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

Each device connected to the Internet has a unique IP address which other machines use to find the device. DNS servers eliminate the need for humans to memorize IP addresses such as 192.168.1.1 (in IPv4), or more complex newer alphanumeric IP addresses such as 2400:cb00:2048:1::c629:d7a2 (in IPv6).
When you type in domain.com into your browser, the browser first needs to figure out the IP address of domain.com. It does this by sending a DNS query to a DNS server. This DNS server is provided by your ISP (Internet Service Provider) or you can use a public DNS server like Google DNS or OpenDNS.

https://www.cloudflare.com/learning/dns/what-is-dns/
DNS lookup is the process by which the browser resolves the domain name to an IP address.
DNS lookup is done by the browser by sending a DNS query to a DNS server.
![]({{"/assets/images/dns.jpeg" | relative_url}})

![]({{"/assets/images/http_history.png" | relative_url}})
![]({{"/assets/images/https.jpeg" | relative_url}})
