# Exchange process

## General workflow for ticket exchange in TCP

This article contains a high-level overview of TCP exchange process. Further details about different types of exchanges can be found later in this guide.

1. **Retrieve/Open the PNR**, validate that it contains the details about originally issued ticket and e-Ticket is still open for use.The itinerary must be modified already \(alternative dates and/or flights selected, changes saved\)

2. **Select the ticket for Exchange/Reissue and select Exchange Option.** TCP supports 4 possible scenarios: 

| Exchange Option | Description |
| :--- | :--- |
| Exchange using new fare quote | TCP fare quotes the new itinerary |
| Exchange using stored fare quote | TCP uses fare quote for new itinerary already stored in the booking file |
| Involuntary change | To use in case of involuntary exchanges |
| Exchange using manual fare quote | Use in cases when it is necessary to store the fare calculation created manually but without using cryptic entries |

3. **Review fare calculation details** and **Select Penalty type:**

* EMD
* To the fare \(Q surcharge\)
* Tax
* No Penalty

4. **Select "Issue ticket"**  to complete the exchange process and issue new ticket or "Go to PNR" to save the changes into fare quote and issue new ticket later.



