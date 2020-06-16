# Penalty collected on EMD

![](../../../.gitbook/assets/image%20%2888%29.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Title</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>RFI code</b>
      </td>
      <td style="text-align:left">D used for fees and charges (financial impact) is automatically added.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>RFI subcode</b>
      </td>
      <td style="text-align:left">
        <p>For example 992 or that one required by the carrier for penalty is</p>
        <p>automatically added.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>FEE description</b>
      </td>
      <td style="text-align:left">Free text &#x2013; the default can be modified by the agent.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>EMD tax</b> (OPTIONAL)</td>
      <td style="text-align:left">and Type and Amount are used in case when a tax is applied to the penalty.
        It is used in some countries where VAT (value added tax) for penalty must
        be calculated. When the VAT is not collected these boxes are not used.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Action on EMD issue</b> 
      </td>
      <td style="text-align:left">
        <p>Print locally or Sent to email</p>
        <p>EMD can be printed locally on the itinerary printer or sent by e-mail.
          If the e-mail address has not been entered in MT element before, it can
          be added at this stage.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Currency</b>
      </td>
      <td style="text-align:left">
        <p>Local currency is added automatically and can be changed to EUR or USD
          if</p>
        <p>necessary.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Amount</b>
      </td>
      <td style="text-align:left">Penalty amount in local currency.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Payment type for EMD</b>
      </td>
      <td style="text-align:left">Cash, Invoice, Card or Other.</td>
    </tr>
  </tbody>
</table>

Card code \(VI, CA, AX etc.\) is automatically added by TCP, it is necessary to enter card number and expiration date, approval code is optional.

![](../../../.gitbook/assets/image%20%2848%29.png)

SVC element is automatically created by TCP and added to PNR: 

![](../../../.gitbook/assets/image%20%2855%29.png)

{% hint style="info" %}
When EMD for specific carrier has not been activated on your market yet, EMD will not be issued.
{% endhint %}

