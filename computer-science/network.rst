Overview
========
textbooks
---------
- Sams Teach Yourself TCP/IP in 24 Hours (在读)
- TCP/IP Illustrated 2nd (在读)

Concepts
--------
- Out-of-band data
  https://en.wikipedia.org/wiki/Out-of-band_data

- Network topology
  https://en.wikipedia.org/wiki/Network_topology#Point-to-point

application layer
=================

HTTP
----

overview
~~~~~~~~
- HTTP: The Definitive Guide (在读, 很多有价值的参考资料在章末)

- What exactly is RESTful programming?
  http://stackoverflow.com/questions/671118/what-exactly-is-restful-programming

- What is Common Gateway Interface (CGI)?
  http://stackoverflow.com/questions/2089271/what-is-common-gateway-interface-cgi

- Basic access authentication
  https://en.wikipedia.org/wiki/Basic_access_authentication

- HTTP cookie
  https://en.wikipedia.org/wiki/HTTP_cookie

- Same-Origin Policy (SOP)
  https://en.wikipedia.org/wiki/Same-origin_policy

- Cross-origin resource sharing (CORS)

  * wiki
    https://en.wikipedia.org/wiki/Cross-origin_resource_sharing

  * HTTP access control (CORS)
    https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS

- Cross-Site Scripting (XSS)
  https://en.wikipedia.org/wiki/Cross-site_scripting

- Cross-Site Request Forgery (CSRF)

  * wiki
    https://en.wikipedia.org/wiki/Cross-site_request_forgery

  * SameSite cookie to prevent CSRF attack
    https://scotthelme.co.uk/csrf-is-dead/

- Session fixation
  https://en.wikipedia.org/wiki/Session_fixation

request methods
~~~~~~~~~~~~~~~
- PUT vs POST in REST
  http://stackoverflow.com/questions/630453/put-vs-post-in-rest

- HTTP GET with request body
  http://stackoverflow.com/questions/978061/http-get-with-request-body

URI
~~~
- Cool URIs don't change
  https://www.w3.org/Provider/Style/URI

header fields
~~~~~~~~~~~~~

request context
...............
- Referer
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Referer

connection management
.....................
- Connection
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Connection

content negotiation
...................
- Accept-Encoding
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept-Encoding

message body information
........................
- Content-Type
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Type

  * charset parameter

    - Setting the HTTP charset parameter
      https://www.w3.org/International/articles/http-charset/

- Content-Length
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Length

- Content-Encoding
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Encoding

transfer coding
...............
- Transfer-Encoding
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Transfer-Encoding

download
........
- Content-Disposition
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Disposition

controls
........
- Expect
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Expect

proxies
.......
- X-Forwarded-Host
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Forwarded-Host

- X-Forwarded-For
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Forwarded-For

caching
.......
- Vary

  * MDN
    https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Vary

  * Best Practices for Using the Vary Header
    https://www.fastly.com/blog/best-practices-using-vary-header/

- Cache-Control
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control

cookies
.......
- Set-Cookie
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie

email
-----
RFC2822: Internet Message Format

file sharing and printing
-------------------------

Network File System Protocol
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Internet Printing Protocol
~~~~~~~~~~~~~~~~~~~~~~~~~~

CUPS: Common Unix Printing System
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- network printing from ubuntu
  https://help.ubuntu.com/community/NetworkPrintingWithUbuntu

SMB/CIFS protocol
~~~~~~~~~~~~~~~~~
- SMB/CIFS wiki
- samba
  * samba (Wikipedia)
  * samba (ubuntu community wiki)
  * samba file server (ubuntu community wiki)
  * samba print server (ubuntu community wiki)
  * SambaServerGuide (ubuntu community wiki)
  * mountWindowsSharesPermanently (ubuntu community wiki)

remote management
-----------------
SNMP
~~~~
- pysnmp doc
  http://pysnmp.sourceforge.net/docs/snmp-history.html
- snmp wiki
  https://en.wikipedia.org/wiki/Simple_Network_Management_Protocol
- management information base
  https://en.wikipedia.org/wiki/Management_information_base

domain name system (DNS)
------------------------


Multicast DNS
~~~~~~~~~~~~~
- mDNS wiki
  https://en.wikipedia.org/wiki/Multicast_DNS

anti-censorship
---------------

DNS poisoning
~~~~~~~~~~~~~

- 域名服务器缓存污染
  https://zh.wikipedia.org/wiki/域名服务器缓存污染

- 浅谈HTTP劫持、DNS污染的影响及解决办法
  https://www.cloudxns.net/Support/detail/id/2249.html

Shadowsocks
~~~~~~~~~~~
- SS 详解
  http://rt.cn2k.net/?p=214
  http://rt.cn2k.net/?p=217
  http://rt.cn2k.net/?p=221

- SS 使用说明
  http://rt.cn2k.net/?p=354

- Shadowsocks + GfwList 实现 OpenWRT / LEDE 路由器自动翻墙
  https://cokebar.info/archives/962

- TCP 方式查询解决 DNS 污染问题
  https://cokebar.info/archives/1053

- Shadowsocks + ChnRoute 实现 OpenWRT / LEDE 路由器自动翻墙
  https://cokebar.info/archives/664

misc
----
Discard Protocol
~~~~~~~~~~~~~~~~
- discard protocol wiki
  https://en.wikipedia.org/wiki/Discard_Protocol

Internet Relay Chat (IRC) Protocol
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- freenode nickname registration
  http://freenode.net/kb/answer/registration

- Konversation/Configuring SASL authentication
  https://userbase.kde.org/Konversation/Configuring_SASL_authentication

- irssi


network layer
=============

Internet Protocol (IP)
----------------------
- Routing selection: specificity vs metric
  http://serverfault.com/questions/648276/routing-selection-specificity-vs-metric
- ip address scope parameter
  http://serverfault.com/questions/63014/ip-address-scope-parameter
- Bogon filtering
  https://en.wikipedia.org/wiki/Bogon_filtering
- Martian packet
  https://en.wikipedia.org/wiki/Martian_packet
- find your public IP address
  http://eth0.me

Internet Protocol Security (IPsec)
----------------------------------
- Internet Key Exchange (IKE, IKEv1, IKEv2)

  * strongSwan

    - Introduction to strongSwan
      https://wiki.strongswan.org/projects/strongswan/wiki/IntroductionTostrongSwan

    - Introduction to strongSwan: IKEv2 Remote Access Client Configuration
      https://wiki.strongswan.org/projects/strongswan/wiki/IKEv2ClientConfig

link layer
==========

wireless
--------

- IEEE 802.11ac standard
  https://en.wikipedia.org/wiki/IEEE_802.11ac

- Femtocell wiki
  https://en.wikipedia.org/wiki/Femtocell
