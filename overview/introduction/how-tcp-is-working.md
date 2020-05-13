# How TCP is working

* The first, second or subsequent exchange before departure – the Fare calculation is created based on the entry &gt;FQ&lt;.
* The first, second or subsequent reissue after departure – the Fare calculation is created based on the entry with the original ticketing date &gt;FQ.Tddmmmyy&lt;.
* If the desired Fare calculation is not returned using the entries above, TCP offers more FQ options for automatic calculation such as:

  * the possibility to add PTC \(passenger type code – e.g. YTH for youth, SRC for senior citizen etc.\) or account code in case of private Fares filed by the carriers.
  * &gt;FQ.Hddmmmyy&lt; = pricing with the fare valid on the date entered and current taxes.
  * &gt;FQ@Fare basis&lt; = pricing with current fare and taxes, specified fare basis used

* Schedule changes – used in cases such as change of flight, date and routing involuntarily. In this case no calculation is required, but all ticketing data are copied from the previous/original ticket.
* Manual mask - which can be used by the agent to store the Fare completely manually but without using cryptic entries.
* For exchanges before departure - the original PNR, where the ticket was issued or new PNR can be used. Then the original ticket number must be entered manually by the agent.
* Filed Fare and Exchange mask are stored and prepared for exchange/reissue automatically.
* Filed Fare already stored in PNR can be used as well.
* There are 3 ways how to collect a penalty:

  * on EMD – SVC element is created and EMD is automatically issued during the exchange/reissue process.
  * as a tax
  * to the Fare as Q surcharge in Fare calculation

* TCP is checking the name of passenger in PNR with the name of passenger on the original ticket and if it doesn’t match, warning message is displayed.
* The exchange/reissue of IT tickets – see example later of this manual.

