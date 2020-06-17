# Copy option - multiple passengers

As already mentioned in the Introduction chapter, Filed Fare and Exchange masks must be stored for each passenger separately. TCP has the ability to copy the data from already created Filed Fare for the first passenger to the masks for other passengers having the same Fare and PTC \(passenger type code\) in order for the agent not to repeat the process for each passenger separately.

![](../.gitbook/assets/image%20%28105%29.png)

The masks for the first passenger have been already created, now it is possible to copy these masks for all other passengers having the same Fare and the same PTC \(ADT in this example\).

{% hint style="info" %}
The other passenger types \(e.g CHD, INF, SRC\) masks has to be created separately. 
{% endhint %}

