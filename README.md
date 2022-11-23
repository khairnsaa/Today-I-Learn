# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

 some new things i've learn today
 
 ## What is the difference between HTTP and HTTPS?
 HTTP stands for **Hypertext Transfer Protocol**. It is a protocol used by a client and server that allows you to communicate with other websites. HTTP uses TCP (Transmission Control Protocol), generally over port 80, to send and receive data packets over the web.

HTTPS stands for **Hypertext Transfer Protocol Secure** (also referred to as HTTP over TLS or HTTP over SSL). HTTPS also uses TCP (Transmission Control Protocol) to send and receive data packets, but it does so over port 443, within a connection encrypted by [Transport Layer Security](https://www.keycdn.com/support/what-is-ssl-tls) (TLS).

The difference between the two protocols is that HTTPS uses TLS (SSL) to encrypt normal HTTP requests and responses. As a result, HTTPS is far more secure than HTTP. A website that uses HTTP has HTTP:// in its URL, while a website that uses HTTPS has HTTPS://.
 
 ## When would we use the “NoSQL” Database?
The usage of a Non-relational database depends on some general points that the developers may find. NoSQL is typically good for unstructured data - usually, there’s no need to explicitly define the schema upfront. It also favors a denormalized schema due to no support for JOINs per the RDBMS world. So you would usually have a flattened, denormalized representation of your data.

It tends to be simple to scale out NoSQL solutions. Adding more nodes to replicate data is one way to offer both more scalability and more protection against data loss if one node goes down. But again, depends on the NoSQL DB/configuration. NoSQL does not necessarily mean "data loss" as we infer.
