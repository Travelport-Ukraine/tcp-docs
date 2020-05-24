# Select additional options

Once you select Exchange option scroll down to additional section.

![](../../.gitbook/assets/image%20%2864%29.png)

In order to get new Fare Quote you have to select additional parameters like passenger name, choose segments and optionally additional modifiers.

![](../../.gitbook/assets/image%20%2872%29.png)

{% hint style="danger" %}
  
**Missing ticket data** – this field is used in case when the agent must add some information necessary for the exchange, which **cannot be identified by TCP**, e.g. the Fare amount in case of I**T tickets** or **XF tax breakdown**, when it is not possible to identify it from the already exchanged ticket or PNR.
{% endhint %}

![](../../.gitbook/assets/image%20%2867%29.png)

![](../../.gitbook/assets/image%20%2844%29.png)

### Select additional options

| Option | Description |
| :--- | :--- |
| **Passenger** | Is selected automatically, but the selection can be changed by the agent. **Passenger type code – PTC** is automatically copied from the “Name” element but can be changed by the agent when some special discount is to be applied. |
| **Segments** | Must be selected by the agent. In case of reissue after departure, already flown segments must be selected as well, because the entire journey must be recalculated from the origin. |

![](../../.gitbook/assets/image%20%2875%29.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Additional options</th>
      <th style="text-align:left">Which date will be used for recalculation (as per IATA rules).</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Before departure</b>
      </td>
      <td style="text-align:left">
        <p><em>Is the first coupon modified?</em>
        </p>
        <p><b>Yes</b> - current Fare and current taxes will be used for recalculation
          (FQ with today&#x2019;s date).</p>
        <p><b>No</b> &#x2013; recalculation will be done with previous/original ticketing
          date. This date is mostly added by TCP automatically, but sometimes (in
          case of the second exchange/reissue) must be added by the agent.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>After departure</b>
      </td>
      <td style="text-align:left">Recalculation will be done with previous/original ticketing date. This
        date is mostly added by TCP automatically, but sometimes (in case of the
        second exchange/reissue) must be added by the agent.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>FQ.H</b>
      </td>
      <td style="text-align:left">Historical Fare but current taxes will be used for recalculation (nonstandard
        procedure).</td>
    </tr>
  </tbody>
</table>![](../../.gitbook/assets/image%20%2851%29.png)

|  |  |
| :--- | :--- |
| **Carrier** | It is not always necessary to show, only in exceptional cases. |
| **Account code** | For private fares with account code. |
| **CUR** | Currency should be entered in case when the original ticket is issued in other currency than the local currency \(e.g. in USD or EUR\). |
| **Additional modifiers** | Any other FQ modifier which can be used for new calculation such as FXD or \*:BFn \(n = number of Fare Family/branded Fare number to receive the fare with baggage\), no stopover indicator, fare break point indicator, private fare indicator etc.  |

{% hint style="warning" %}
FQ calculation date is mostly added by TCP automatically, but can be changed by the agent. Sometimes in case of the second or subsequent exchange/reissue this date must be added by the agent either using the calendar or typing the date manually.
{% endhint %}

![](../../.gitbook/assets/image%20%2877%29.png)

{% hint style="info" %}
**Pricing by Fare basis** – sometimes it is necessary to enter the required Fare basis code in order to specify which Fare should be used \(e.g. Fare with baggage\)
{% endhint %}

![](../../.gitbook/assets/image%20%2880%29.png)

After all the necessary information has been added, the fare calculation made by Galileo will be returned and can be compared to the original / previous ticket.

