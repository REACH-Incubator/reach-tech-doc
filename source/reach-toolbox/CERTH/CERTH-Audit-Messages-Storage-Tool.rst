Overview of CERTH Audit Messages Storage Platform
=============================================

CERTH Audit Messages Storage is a tool that enables the storage of audit messages in the Blockchain. It also provides an Explorer (User Interface) which enables retrieval of the stored messages using several searching criteria as well the validation of the integrity of the messages. 

The purpose is to enable:

1. Auditability and non-repudiation of actions via the immutable storage of audit messages in the Blockchain
2. Traceability of the audit messages.
3. Integrity check of the stored messages. 


Getting access to the Infrastructure
------------------------------------

The Audit Messages Storage Platform will be available online for everyone who wants to save their critical data in the Platform. The users have to register to the Platform using their e-mail and password and they will have access to the functionalities provided.

.. note:: To obtain access, contact us by mail (<krinidis@iti.gr>, <ggogos@iti.gr>) to the consortium address.

Audit messages storage
----------------------

Two interoperable information systems send a message to each other using SoA and web services. An intermediate system filters critical messages,provided by the participants, encrypts the sensitive parts if applicable, and encodes them in an appropriate format (e.g. JSON). The intermediate system sends the critical messages to the Smart Contracts deployed in the Blockchain network. The Smart Contracts store the critical messages in the Blockchain, in an immutable way.

.. image:: img/Audit4.PNG


Audit messages tracing
----------------------

An authorized user enters a Swagger API interface and searches stored message logs based on a set of criteria. The users who provided the critical data, can check who asks access to their data and they give permission if needed.

.. image:: img/Audit5.PNG


Messages integrity verification
-------------------------------

The Swagger queries the Smart Contracts deployed for the specific logs and returns them in JSON format. If the User is authorized, they are able to see the details of the returned message and also verify the integrity of the message.

.. image:: img/Audit6.PNG


Use case
--------
All users of the tool can store their sensitive data and query others data respectively. The tool is adapted for systems in which there is an exchange of messages between distributed components using SoA, using a blockchain system with deployed Solidity smart contracts to store logs for the exchange of the messages including metadata, in a secure an immutable way, and there is also a need to search for this log and check its integrity.   
