```bash
id
```

<table>
<tbody>
  <tr>
    <td>
    <ol>
    <li>A user provides credentials to the Domain Controller.</li>
    <li>The DC returns a TGT./li>
    <li>The user requests a TGS for the web service on Web Server./li>
    <li>The DC provides a TGS./li>
    <li>The user sends the TGT and TGS to the web server./li>
    <li>The web server service account use the user's TGT to request a TGS for the database server from the DC./li>
    <li>The web server service account connects to the database server as the user.</li>
    </ol>
    </td>
    <td><img style="float: right;" src="https://i.imgur.com/s5T5QSD.png"></td>
  </tr>
</tbody>
</table>



