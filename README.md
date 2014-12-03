PaymentViaMobilePhone
=====================

We are proposing a mobile payment system that will provide confidentiality, integrity, authentication and non-repudiation for the different users involved. Like mentioned earlier, we will provide confidentiality and integrity between the payer and the merchant through symmetric encryption. The symmetric key will be generated through a handshake protocol between the payer client and the merchant server, and in the process they will both be authenticated. The merchant server will be authenticated through their public key certificate, and the client will be authenticated via SMS through their communication provider. 

The final order will then be authorized by a payment platform that will make sure that the order is the same from both client and server. The payment order will then be finally authorized by a payment gateway that will compare order given by the payment platform and the merchant server. 
	
Key Word: Mobile, symmetric key, asymmetric encryption, handshake protocol, SMS
