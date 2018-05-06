# EDS
effective delivery system

This is kind of a white paper on the effective delivery system.
We currently rely on emails and email forwarding to sms messages for monitoring on a smartphone usually. 
How to ensure something actually gets delivered, like SNMP messages or MSP monitor alerts, etc. 

someway or somehow this idea should ensure delivery and receipt of the email, maybe by sending until a read receipt is returned?


messagetest .DeliveryNotificationOptions = DeliveryNotificationOptions.OnSuccess;

	Member name	Description
  
	Delay	

Notify if the delivery is delayed.

	OnFailure	

Notify if the delivery is unsuccessful.

	OnSuccess	

Notify if the delivery is successful.

that was from msdn about the methods, maybe just add this to snmp listener emailer... nuff said
