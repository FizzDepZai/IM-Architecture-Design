# IM-Project

An instant messaging system supporting cross-platforms.

XMPP (also known as Jabber) is the leading open standard for instant messaging (IM) and is an open XML technology for real-time communication. Since 2004, it's been an approved standard of the IETF (the same organization that standardized email and World Wide Web protocols). A rich set of extensions to the protocol are maintained by the Jabber Software Foundation, by which anyone may implement an XMPP service and interoperate with other organizations' implementations. Today, XMPP is used by leading companies, millions of users worldwide and is the best choice for open real-time collaboration. Although many server, client, and library implementations are distributed as free and open-source software, numerous freeware and commercial software implementations also exist.

1. eJabberd is the most famous open source Jabber server written in Erlang and is used by Whatsapp, some other tech giants such as Facebook and Google went away from it because it was difficult to find qualified developers.

2. Openfire is a real time collaboration (RTC) server licensed under the Open Source Apache License. It uses the only widely adopted open protocol for instant messaging, XMPP (also called Jabber). It is easy to setup and administer, but offers enterprise level security and performance.

However XMPP is a heavyweight protocol (streaming XML message) with high overhead in the network, which cause long latency when sending a message (long-polling technique) and also battery draining issue on mobile devices. Companies such as Facebook uses MQTT protocol at the client-side to improve connection performance and battery life. MQTT stands for MQ Telemetry Transport. It is a publish/subscribe, extremely simple and lightweight messaging protocol, designed for constrained devices and low-bandwidth, high-latency or unreliable networks. MQTT is being standardized by OASIS as a communication protocol for Internet of Things (IoT) and Machine-to-Macine (M2M) applications.

<b>References:</b><br>
- [The WhatsApp Architecture Facebook Bought For $19 Billion](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)
- [What is WhatsApp's server architecture?](https://www.quora.com/What-is-WhatsApps-server-architecture)
- [What is the technology behind wechat, whatsapp and other messenger apps?](http://stackoverflow.com/questions/19640703/what-is-the-technology-behind-wechat-whatsapp-and-other-messenger-apps)
- [Erlang Programming Language - Build massively scalable soft real-time systems](https://www.erlang.org/)
- [eJabberd - XMPP Messaging Server based on Erlang](https://docs.ejabberd.im/)
- [Openfire - XMPP Messaging Server based on Java](http://www.igniterealtime.org/projects/openfire/)
- [What is MQTT?](http://mqtt.org/faq)
- [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki)
- [Eclipse Paho MQTT Client in Java](http://www.eclipse.org/paho/)
- [Bulding Facebook Messenger with MQTT](https://www.facebook.com/notes/facebook-engineering/building-facebook-messenger/10150259350998920)
- [Why Facebook is using MQTT on mobile](https://www.ibm.com/developerworks/community/blogs/mobileblog/entry/why_facebook_is_using_mqtt_on_mobile?lang=en)

# Full-Stack

![Alt text](http://docs.aws.amazon.com/gettingstarted/latest/wah-linux/images/architecture_linux.png)

<b>References:</b><br>
- [Full Stack - Facebook Engineering](https://www.facebook.com/notes/facebook-engineering/the-full-stack-part-i/461505383919/)
- [Scaling Out - Facebook Engineering](https://www.facebook.com/notes/facebook-engineering/scaling-out/23844338919/)
- [Scaling Facebook to 500 Million Users and Beyond](https://www.facebook.com/notes/facebook-engineering/scaling-facebook-to-500-million-users-and-beyond/409881258919/)
- [Scaling memcached at Facebook](https://www.facebook.com/notes/facebook-engineering/scaling-memcached-at-facebook/39391378919/)
- [Building Software Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/Stanford-DL-Nov-2010.pdf)
- [Software Engineering Advice from building Large-Scale Distributed Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf)
- [Challenge in building Large-Scale Information Retrieval Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/WSDM09-keynote.pdf)
- [Building Large-Scale Internet Service - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/SOCC2010-keynote-slides.pdf)
- [C10K Problem](https://en.wikipedia.org/wiki/C10k_problem)

# Disk Storage

<b>References:</b><br>
- [Introduction to Microsoft Azure Storage](https://azure.microsoft.com/en-us/documentation/articles/storage-introduction/)
- [To BLOB or NOT to BLOB](http://research.microsoft.com/apps/pubs/default.aspx?id=64525)
- [Network-attached Storage](https://en.wikipedia.org/wiki/Network-attached_storage)
- [How is disk speed measured](http://serverfault.com/questions/206370/how-is-disk-speed-measured-and-what-is-fast-how-long-should-a-copy-of-1500-gb-t)
- [File System Comparison](http://research.microsoft.com/apps/pubs/default.aspx?id=64525)
- [Linux File System explain](https://help.ubuntu.com/community/LinuxFilesystemsExplained)

# OS and Virtualization

<b>References:</b><br>
- [Windows Server 2012 Virtualization](https://www.microsoft.com/en-us/server-cloud/solutions/virtualization.aspx)
- [Xen Virtualization](http://www.xenproject.org/)
- [KVM - Kernel Virtual Machine](http://www.linux-kvm.org/page/Main_Page)

# Web and Application Server

<b>References:</b><br>
- [What are the pros and cons of Node.js versus Apache web server?](https://www.quora.com/What-are-the-pros-and-cons-of-Node-js-versus-Apache-web-server)
- [What specifically makes Node.js more scalable than Apache?](http://stackoverflow.com/questions/16578874/what-specifically-makes-node-js-more-scalable-than-apache)
- [What is the difference between application server and web server?](http://stackoverflow.com/questions/936197/what-is-the-difference-between-application-server-and-web-server)
- [Tomcat Websphere Comparison - Choosing The Right Java Server Solution - See more at: https://www.mulesoft.com/tcat/tomcat-websphere#sthash.Sbi1SndB.dpuf](https://www.mulesoft.com/tcat/tomcat-websphere)

# Database

<b>References:</b><br>
- [PostgreSQL - High Availability, Load Balancing, and Replication](http://www.postgresql.org/docs/9.0/static/high-availability.html)
- [MySQL Enterprise - High Availability](https://www.mysql.com/products/enterprise/high_availability.html)
- [MySQL Cluster - High Availability](https://www.mysql.com/products/cluster/availability.html)
- [SQL Server 2016 - High Availability](https://msdn.microsoft.com/en-us/library/ms190202.aspx)
- [SQL Server 2014 - High Availability](https://msdn.microsoft.com/en-us/library/cc645993(v=sql.120).aspx#High_availability)

# OAuth

<b>References:</b><br>
- [Security setup for RESTful web services - IBM](http://www.ibm.com/developerworks/websphere/library/techarticles/1312_ahmed/1312_ahmed.html)
- [WS Security - IBM](http://www.ibm.com/developerworks/webservices/tutorials/ws-understand-web-services4/ws-understand-web-services4.html)
- [OAuth 2.0 clients in Java programming - IBM](http://www.ibm.com/developerworks/library/se-oauthjavapt1/)
- [Implementing OAuth 2.0 on IBM WebSphere DataPower - IBM](http://www.ibm.com/developerworks/websphere/library/techarticles/1208_rasmussen/1208_rasmussen.html)
- [Enabling OAuth2.0 Service Provide on IBM WebSphere Application Server](http://www.ibm.com/developerworks/websphere/techjournal/1305_odonnell1/1305_odonnell1.html)
- [Using OAuth 2.0 to access Google APIs](http://developers.google.com/identity/protocols/OAuth2)
- [Google OAuth 2.0 Playground](http://developers.google.com/oauthplayground)
- [The OAuth 2.0 Authorization Framework](http://tools.ietf.org/html/rfc6749)

# Push Notification

Due to the fact that every Google service is blocked in China by the government firewall, to send and receive push notification for device in China region we must use other push service such as Baidu. 

<b>References:</b><br>
- [Baidu Push Service](http://push.baidu.com/)

# Architecture Considerations (Key Design Principle)

To avoid the risk of depending only to single vendor significantly, the architecture should be loosely coupled with the vendor's infrastructure. This consideration is not just from a cost standpoint, but also from an operations standpoint. This include a need to keep operating costs down by always using the most efficient software on the market, a need for fast expansion with limited funds, which could be made difficult if every new CPU represented thousands of dollars of licensing fees, or ease-of-development concerns.

For companies that are just starting out, and are unsure of how much complexity their architecture will require in the future, open source product is a safe bet because it allows them to get a very stable iteration of their infrastructure up and running for a very small initial investment. This leaves them plenty of breathing room to expand their network as needed, either by paying developers and architects to build a lightweight customized solution precisely matched to their needs, which can be expanded in response to the company's growth, or even just by saving them enough money that it's possible to migrate to a proprietary solution if their company reaches a stage where this is the most prudent decision. While for companies who are loaded with developers who like to use the latest and greatest in technology, an open source infrastructure can mean that there's enough money left over to try out other products, and because they are are so widely adopted, it's often very simple to integrate that work into the existing network if it proves successful. Avoiding the weight of massive annual license charges is important for these companies to maintain the sense that they are agile and will be able to respond to changes in the marketplace without making money the default deciding factor. 

<u><b>Conclusion</b></u><br>
The cost of using free and open source product will only be as expensive as the hardware to run it and the developer hours to configure it, and apart from all these cost concerns, open source product comes out looking pretty good. Free, lightweight, and simple, yet powerful, efficient, and proven in both production and development environments contributes to a major factor in the decision making process.
