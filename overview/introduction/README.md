# Introduction

TCP is the new generation of GEM based on uAPI communication, the new application that automates exchanges/reissues of tickets. The biggest advantage of TCP is that it is independent on Galileo Smartpoint / Galileo Desktop and therefore it can be also used with **Galileo terminal**.

TCP has no its own pricing system; it is using exclusively Galileo 360 Fare system.

With this application it is possible to receive the new Fare calculation based on revised itinerary in PNR for tickets “before departure” when the travel has not started yet, as well as for tickets “after departure”, it means for partly used tickets.  After the Fare calculation is agreed, the Filed Fare and the Exchange mask prepared for exchange/reissue process are stored in the PNR. The ticket can be exchanged/reissued immediately or later based on stored ticketing data.

For the exchange/reissue process it is also possible to use the already stored Filed Fare or to create manual Fare mask.

New ticket issued in exchange has the pricing indicator B or M and it is always the agent’s responsibility to check the Rule conditions especially Category 16 applied to the appropriate Fare as it is done at the time being. 

TCP compares the Fare and taxes from the original ticket with the new Fare calculation returned by the Galileo pricing system and automatically applies the difference, but the agent is able to modify the results manually. TCP can also be used with quite new PNRs, where the original ticket was not issued but only in case of exchange before departure, if the new itinerary is still complete. Another advantage of TCP are exchanges / reissues in case of “involuntary changes”, when all ticketing data are copied from the original ticket according to IATA resolution. That’s why TCP can be used nearly in 98% of all exchanges.

With TCP it is possible to collect penalty as a new tax, to the Fare as Q surcharge or to collect penalty on EMD which is automatically issued during the exchange/reissue process.



