# IONMP
Protocol specification for IONMP. This repository only has files and issues related to the protocol specification and allied activities. 

In the current scenario, for IOT, different flavours of existing protocols like HTTP, MQTT, etc., are being used. However these protocols were designed for other purposes and each implementor uses these protocols for IOT in a way that is suitable for them. The absence of a standard introduces lack of interoperability and also limits the flexibility of operation. 

Entities of the IOT world have to continously communicate various types of data. The data either may be readings from sensors or may be instructions to activate output devices. In this document, the entities which are end-points are referred to as IONs – Input or Output Node. 

There are numerous internet protocols that govern the communication between various entities. IONMP works in concert with these protocols by using the payload part for the messaging. Certain protocols like MQTT use a part of the payload for its own messaging. In such cases, the remaining part of the payload will be the IONMP payload. IONMP enables the creation of an infrastructure of network hosts (called IOT gateways servers) to which IONs can send registrations and messages.  
