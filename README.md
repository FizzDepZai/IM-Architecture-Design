# IM-Project
An instant messaging system supporting cross-platforms.

# Architecture Considerations (Key Design Principle)

The huge initial investment required to integrate a vendor's infrastructure (i.e. Microsoft Azure) is a major factor of generating what is known as "vendor dependency", when a company feels bound to continue using a specific vendor's software, or buy that company's integrated extension products instead of a competitor's, simply because they have already invested so much money into that vendor's products.

There are two ways to think about this phenomenon.  A huge, very wealthy company might like the fact that they can get all of their solutions from a single, familiar vendor - for them, the high price is simply the cost of using a well-established solution, and if they ever did need to migrate to a different service, they'd have the cash to finance the move.  On the other hand, a much greater number of companies would view a "vendor depedency" scenario as extremely undesirable, not just from a cost standpoint, but from an operations standpoint as well. This include a need to keep operating costs down by always using the most efficient software on the market, a need for fast expansion with limited funds, which could be made difficult if every new CPU represented thousands of dollars of licensing fees, or ease-of-development concerns.

For companies that are just starting out, and are unsure of how much complexity their architecture will require in the future, open source product is a safe bet because it allows them to get a very stable iteration of their infrastructure up and running for a very small initial investment.  This leaves them plenty of breathing room to expand their network as needed, either by paying developers and architects to build a lightweight custom Tomcat-based solution precisely matched to their needs, which can be expanded in response to the company's growth, or even just by saving them enough money that it's possible to migrate to a proprietary solution if their company reaches a stage where this is the most prudent decision. While for companies who are loaded with developers who like to use the latest and greatest in technology, a open source infrastructure can mean that there's enough money left over to try out other products, and because theya are so widely adopted, it's often very simple to integrate that work into the existing network if it proves successful.  Avoiding the weight of massive annual license charges is important for these companies to maintain the sense that they are agile and will be able to respond to changes in the marketplace without making money the default deciding factor. 

The cost of using free and open source product will only be as expensive as the hardware to run it and the developer hours to configure it, and aparat from all these cost concerns, open source product comes out looking pretty good.  Free, lightweight, and simple, yet powerful, efficient, and proven in both production and development environments contributes to a major factor in the decision making process. 

# Full-Stack

![Alt text](http://docs.aws.amazon.com/gettingstarted/latest/wah-linux/images/architecture_linux.png)

<b>References:</b><br>
- [Full Stack - Facebook Engineering](https://www.facebook.com/notes/facebook-engineering/the-full-stack-part-i/461505383919/)
- [C10K Problem](https://en.wikipedia.org/wiki/C10k_problem)
- [Building Software Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/Stanford-DL-Nov-2010.pdf)
- [Software Engineering Advice from building Large-Scale Distributed Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf)
- [Challenge in building Large-Scale Information Retrieval Systems - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/WSDM09-keynote.pdf)
- [Building Large-Scale Internet Service - Google](http://static.googleusercontent.com/media/research.google.com/en//people/jeff/SOCC2010-keynote-slides.pdf)

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
