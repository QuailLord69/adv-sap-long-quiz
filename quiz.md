## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- This is a modularized approach to the use of services through the net in which several processes are segregated into parts to act and provide services as a server.

2. List and discuss the characteristics of SOA.
- The SOA is a combination of a presentation (HTML), logic (PHP), and a data layer (MySQL) in which they act as separate modules. Instead of the usual software services where all functions share the same location, this method modularizes the process. This solves the problem of the monolithic design where it starts to get difficult and harder to maintain as the process gets more complex.

3. Define Microservices.
- The microservices is a method which takes the modularized approach even further where processes are broken down into smaller parts. 

4. List and discuss the benefits of using Microservices.
- The microservices breaks apart the data and logical layers into smaller pieces. It can allow multiple users to manage different modules or layers without affecting the others. There will be a chance where those users can use different languages at the same time. But, to reduce costs and increase efficiency, most organization limits the number of language used. As microservices expands throughout time, the issue about complexity will arise once again in which the root cause might prove difficult to find. But, there are several available tools that can aid an ever-growing application service.

5. List and discuss the similarities and differences of SOA and Microservices.
- Both the SOA and Microservices utilizes the modularized approach where there is an interface, a logical layer, and a data storage. They also solve the issue that arises in the monolithic method when it comes to more complex systems. But, the microservice approaches this method into an even smaller and detailed scale. In this case, the microservices can grow further and handle more complex processes. Though the use of microservices still depends on the complexity of the planned system. This also means that a monolithic approach is still a viable option for a simpler system.

6. Define Web Services.
- Web services in its most basic sense is service that is made available to the user with the use of the internet. However, delving deeper, web services allows different systems and applications to communicate with each other. This allows a system to request for database stored information from other sources to improve their services.

7. List and discuss the benefits of using Web Services.
- This allows enterprises to improve their services, further increasing the efficiency of their systems. An example to this are online retailers that requires to calculate the shipping fee amount regarding the weight of the item and the destination. These retailers can rely on the provided web services of the shipping company to update the calculated fee in real time. Not only does this increase efficiency but also improve user experience that may boost service usage.

8. List and discuss the characteristics of Web Services.
- **XML-Based:** Provides services with an ease-of-storage with its plain text format, allowing high interoperability.
- **Loosely coupled:** Though web services allows clients to connect and use its features, it does not completely ties them into it. This ensures that clients would not need to adjust as the web service updates.
- **Coarse-grained:** These type of services have fewer but larger components that allows users to easily understand the concepts even with only a few knowledge about software. 
- **Ability to be synchronous or asynchronous:** Allows different forms of callings to retrieve information from the web services. It is where the client will wait for service completion for synchronous or the client continues the process then receives the results at a later time with the asynchronous method.
- **Supports Remote Procedure Calls or RPCs:** Separates the call procedures to the client's addresses and assigns its own different one. This allows callbacks and information invoking from the web service with a different address location and is written as if its a normal procedure call.
- **Supports document exchange:** Allows sharing and integration of documents or information between different applications or systems. Document exhange provides generic representation of complex documents, making it easier to use such data to a different location.

9. List and discuss the distinct roles in Web Services Architecture.
- **Provider:** Makes it so that the web services are available for clients to use in their system.
- **Requestor:** Allows different forms of client applications to request for data from the web services.
- **Broker:** Provides acces to the Universal Description Discovery and Integration in which allows clients to access the web services.
- **Publish:** Informs the broker of an existing web service for client access.
- **Find:** Requests the broker to locate an already published or existing web service.
- **Bind:** Binds or connects the requestor to the found web service allowing them to use its properties.

10. List and discuss the Web Services Components.
- **SOAP:** Simple Object Access Protocol, a cross-platform protocol that allows different applications to communicate with each other.
- **WSDL:** Web Services Description Language, describes the contents of a web service and on how to access them with the use of XML-based language.
- **UDDI:**  Universal Description Discovery and Integration, an open framework that uses the previous said components to make a web service available for the clients.