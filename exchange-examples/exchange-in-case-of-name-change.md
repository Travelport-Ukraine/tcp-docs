# Exchange in case of name change

## in case of name change

TCP allows to reissue ticket by adding the number of original ticket manually. The following scenario examplifies the procedure in case of name change.

The passenger purchased the original ticket to travel from Kyiv to Budapest on the 20th of September in economy class. The ticket was originally issued at the fare of USD 102.00 plus taxes 80UA, 53UD, 398YK, 4ND, 439XW, 928YQ

![](../.gitbook/assets/originalticket1.png)

Name change procedure needs to be applied due to the passenger's marriage.

1. Create new PNR indicating the new surname for the same itinerary. 
2. Fare quote this new itinerary, end and retrieve the PNR. 
3. Open this new booking in TCP

![](../.gitbook/assets/pnr_new.png)

1. Indicate the original ticket number to TCP using the option "Add ticket by number". Once the number has been filled in, click "Add" link

![](../.gitbook/assets/correctadditionoftktnumber.png)5. Please note that the ticket number needs to be indicated without spaces, otherwise an error will be returned

![](../.gitbook/assets/error_tktnumber.png)

6.Once the ticket number has been accepted, Exchange option is available. Further details about the ticket can be obtained by clicking the magnifying glass button:

![](../.gitbook/assets/magnyfyingglass.png)

1. To collapse the detailed view, simply click on this button again:

![](../.gitbook/assets/unfold.png)

1. Select "Exchange using stored fare quote" ![](../.gitbook/assets/exchangeusingfq.png)
2. Once "Exchange using stored fare quote" has been selected TCP automatically compares new fare plus taxes and the original ticket and displays Exchange calculation table. The agent only needs to indicate whether some penalty needs to be charged for ticket change, the option "No penalty" is selected by default.

![](../.gitbook/assets/nopenalty.png)If for exchange ticket a different commission applies, TCP allows to indicate is manually by selecting amount or percentage and indicating the commission value

![](../.gitbook/assets/ticketingcommission.png)

1. In case of additional collection TCP displays drop-down menu to select the payment method.

![](../.gitbook/assets/adcpayment.png)

The endoresement box is automatically filled by TCP with the information from a stored fare quote:

![](../.gitbook/assets/endoresement.png)

When the fare details need to be suppressed by IT/BT modifier, the relevant radio btutton needs to be checked. Otherwise the default option "None" applies

![](../.gitbook/assets/noneitbt.png)

11.Check the exchange calculation table and select whether the new ticket should be issued now or later.

The exemplified scenario uses "Issue the ticket now" option. Do not forget to press the green arrow to complete the exchange procedure.

![](../.gitbook/assets/completeexchange.png)

The new ticket as per new surname has been issued successfully by TCP

![](../.gitbook/assets/namechangeticket.png)

