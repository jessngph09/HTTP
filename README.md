# HTTP IN-CLASS LECTURE

# Introduce: HTTP (HyperText Transfer Protocol)

Consider a scenario where someone wants to request a document from someone. What is the protocol for that, assuming the request and response both utilize snail mail (i.e., the postal service). 

With a partner, write down the steps that the SENDER needs to perform to create and send their request. 
    Sender Actions:
  * Write down addresses (to/from) on the top of the letter and the envelope.
  * Write down the request ("GET")
  * Stamp
  * Send it 

With a partner, write down the steps that the RECEIVER needs to perform to react to the request and send a response. 

 ```java
/** HTTP Client. */
private static HttpClient HTTP_CLIENT = Http.Client.newBuilder()
.version(HttpClient.Version.HTTP_2)            // uses HTTP protocol version 2 where possible
.followRedirects(HttpClient.Redirect.NORMAL)   // always redirects, except from HTTPS to HTTP
.build();
  ```
