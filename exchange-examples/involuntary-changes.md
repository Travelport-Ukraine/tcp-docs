# Involuntary changes

Please find below the workflow how to process an involuntary change in TCP.

![Original ticket](../.gitbook/assets/image%20%28143%29.png)

**Changed itinerary** **–** AF flight PAR - SGN is cancelled and the passengers are rerouted via AMS and BKK with KL carrier. It means that instead 2 segments PRG – SGN there are 3 segments now.

![](../.gitbook/assets/image%20%28184%29.png)

### Open PNR in TCP

![](../.gitbook/assets/image%20%28102%29.png)

### Expand the ticket

![](../.gitbook/assets/image%20%28180%29.png)

### Click to Exchange

![](../.gitbook/assets/image%20%2898%29.png)

The option **“Involuntary changes”** should be selected. No pricing is used, TCP is copying all data from the original ticket.

![](../.gitbook/assets/image%20%28189%29.png)

Once you select Involuntary changes mask will appear

![](../.gitbook/assets/image%20%28181%29.png)

Because routing has been changed, you must specify from which coupon the data is to be copied for the first, second, and third segments.

![](../.gitbook/assets/image%20%28169%29.png)

That is, the data from the first coupon should be copied to the first segment and the data from the second coupon should be copied to the second and third segments.

![](../.gitbook/assets/image%20%28173%29.png)

### Fare calculation and taxes are copied

![](../.gitbook/assets/image%20%28193%29.png)

When the option **“Involuntary changes”** is selected, the code **SKCHG** is automatically added at the beginning of the Endorsement message and you can enter the reason just after the code. The original Endorsement message is moving to the right. At the same time, the letter **S** is also **automatically added** at the beginning of the Fare calculation. **This is according to IATA resolution 735.**

![](../.gitbook/assets/image%20%28147%29.png)

If you have received different requirements from the carrier, you can turn off the **switch** and continue according to the airline instructions.

### Comparison table

![](../.gitbook/assets/image%20%28158%29.png)

![](../.gitbook/assets/image%20%28176%29.png)

{% hint style="success" %}
There will be no additional collection or refund because the Fare calculation, the Fare and all taxes are copied from the original ticket.
{% endhint %}

The rest of the procedure is the same as for the other examples.

