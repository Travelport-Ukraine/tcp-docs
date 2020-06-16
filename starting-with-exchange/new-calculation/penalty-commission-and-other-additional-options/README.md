# Penalty, Commission and other additional options

![](../../../.gitbook/assets/image%20%2845%29.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Additional options</th>
      <th style="text-align:left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><b>Penalty</b>
      </td>
      <td style="text-align:left">There are 3 ways, how to collect a penalty:
        <br />- on EMD
        <br />- as a tax
        <br />- to the Fare.
        <br /><b>No penalty</b> option is set as a default.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Commission</b>
      </td>
      <td style="text-align:left">There are 3 ways, how to enter commission:
        <br />- as a percentage,
        <br />- as an amount,<b><br /></b>- or TCP will take the commission set by the
        carriers in Galileo (GDS automatic).
        <br />In case of private Fares, the commission has been already loaded by the
        carrier and therefore cannot be modified in TCP.
        <br />Zero (0) percent is set as a default.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Fare basis rules warning</b>
      </td>
      <td style="text-align:left">When the option <b>Pricing by Fare basis</b> is used, the system is checking,
        if all Fare conditions are met.
        <br />If yes, &#x201C;RULE VALIDATION MET&#x201D; is returned by the system
        and you can be sure that the calculation is correct and can be used.
        <br
        />If the Fare rules are not met, the appropriate warning message is returned
        by the system and shown in TCP, e.g. BOOKING CLASS FAILURE, ADVANCE PURCHASE
        FAILURE, ROUTING FAILURE etc.
        <br />If such warning message is returned, the agent must check the Fare rule(s)
        and decides if to continue with the exchange/reissue, as it is on his/her
        responsibility.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Other options</b>
      </td>
      <td style="text-align:left">
        <p><b>IT/BT indicator</b> is set automatically if the new Fare used has been
          distributed by the carrier as IT or BT or can be marked manually by the
          agent, if the new ticket should be issued with IT or BT indicator in the
          Fare box.</p>
        <p><b>Endorsement</b> is copied from the new Filed Fare if any or can be added
          or modified by the agent. Each message can be separated by dash (-). It
          is not possible to use asterisk (*) or slash (/). The slash from the endorsement
          automatically stored is changed to dash.</p>
        <p><b>Tour Code</b> is automatically added if the new Fare was loaded with
          Tour Code or is copied from the original ticket.</p>
      </td>
    </tr>
  </tbody>
</table>

