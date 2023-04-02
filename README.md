<h1>
  Unrecognized option or missing or extra parameter(s) in {.ovpn file}: data-ciphers-falback
</h1>
<details>
  <summary>Read more</summary>
  <h2>Keywords</h2>
  <ul>
    <li>data-ciphers-fallback</li>
    <li>data-ciphers</li>
    <li><a href="https://community.openvpn.net/openvpn/wiki/CipherNegotiation">Cipher Negotiation</a></li>
  </ul>
  
  <h2>Affected Version(s)</h2>
  <ul>
    <li>2.4.7</li>
  </ul>

  <h2>Solution(s)</h2>
  <p>
    <a href="https://forums.openvpn.net/viewtopic.php?t=31516">Fix #1</a> - Comment out the 'data-ciphers-fallback' and 'data-ciphers' parameters.
    <pre>data-ciphers AES-256-CBC</pre>
  </p>
</details>
