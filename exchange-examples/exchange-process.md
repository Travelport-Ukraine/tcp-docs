# Exchange process

TCP Exchange process is driven by uAPI JSON code which is effectivly used in our other successful projects.

## General workflow for ticket exchange in TCP

This article contains a high-level overview of TCP exchange process. Further details about different types of exchanges can be found later in this guide.

1. Retrieve the PNR, validate that it contains the details about originally issued ticket and e-Ticket is still open for use.

    The itinerary must be modified already \(alternative dates and/or flights selected, changes saved\)

2. Select the fare quote using which ticket exchange should be run. TCP supports 

   3 possible scenarios: Exchange using new fare quote \(when TCP fare quotes the new itinerary\); Exchange using stored fare quote \(when TCP uses fare quote for new itinerary already stored in the booking file\); Exchange using manual fare quote \(used in cases when it is necessary to store the fare calculation created manually but without using cryptic entries\).

3. Review fare calculation details, select Penalty type \(EMD-S, Q surcharge, Tax\).
4. Select "Issue ticket"  to complete the exchange process and issue new ticket OR "Go to PNR" to save the changes into fare quote and issue new ticket later.
5. In case the option "Issue ticket" was selected TCP should display the newly issued ticket. When the agent opts for "Go to PNR" on the new screen TCP a screen displays the PNR with fare quote.

