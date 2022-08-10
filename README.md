# JMS-QUEUE

JMS Tutorial
JMS (Java Message Service) is an API that provides the facility to create, send and read messages. It provides loosely coupled, reliable and asynchronous communication.

JMS is also known as a messaging service.

Understanding Messaging
Messaging is a technique to communicate applications or software components.

JMS is mainly used to send and receive message from one application to another.


Requirement of JMS
Generally, user sends message to application. But, if we want to send message from one application to another, we need to use JMS API.

Consider a scenario, one application A is running in INDIA and another application B is running in USA. To send message from A application to B, we need to use JMS.

Advantage of JMS
1) Asynchronous: To receive the message, client is not required to send request. Message will arrive automatically to the client.

2) Reliable: It provides assurance that message is delivered.


Messaging Domains
There are two types of messaging domains in JMS.

Point-to-Point Messaging Domain
Publisher/Subscriber Messaging Domain
1) Point-to-Point (PTP) Messaging Domain
In PTP model, one message is delivered to one receiver only. Here, Queue is used as a message oriented middleware (MOM).

The Queue is responsible to hold the message until receiver is ready.

In PTP model, there is no timing dependency between sender and receiver.

jms point to point model
![jms-point-to-point-model](https://user-images.githubusercontent.com/39576908/183791154-ca1dd48e-0298-4bd4-90ec-4180b9f59343.gif)


