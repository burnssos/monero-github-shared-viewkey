# monero-github-shared-viewkey
Use to test the "notary" potential of Monero Secret View Key and Payment ID field.
Any Monero sent to either public address will be used to develop, advance, and test the potential of this "notary" idea. All else fails excess Monero will be sent to the development of Monero or OpenAlias. 
<br>
<br>
https://getmonero.org/get-started/contributing/
<br>
https://openalias.org/#contribute
<br>
<br>
github-share
<br>
XMR: 42aA6DgMCa3gigJLnahb8cZeSRbE3p94VgNM4BdnnirL7UdcQ7WMkBE42nwqkuJYLc3yffToCY4MSLUaXyBnRHsXMofTJuL
<br>
<br>
github-other-share
<br>
XMR: 48H7BxiWSebSeeq1RHxes8Ha3FtFTGLzK9eZ84yyHFopQCDXB5HTjoKcMPPpZaN5zDhELN1D1oibDDiXHBBYEwqtByZwHAd
<br>
<br>
I used the sha256 hash of "getmonero.org" (which is: "8e420d4ef5ec550c289990a6881307a78e4ab441dccb4cbbb0dda8bb6ef18b5d") as a private spend key as described in discussions by dnaleor (https://github.com/monero-project/monero/issues/3772) where they stated: 
<br>
<br>
"
<br>
there is a lesser known variant of proof of existance and you don't need OP_RETURN (for BTC) or paymentIDs (for XMR):
<br>
You can just hash your file and use it as a private (spend) key. For monero, then construct the view key based on that spend key (https://xmr.llcoins.net/addresstests.html) and send a very small payment to the address. When you reveal the private (spend) key [or sign a message with it], you prove that you created that transaction based on the hash of the file at a certain point in history.
<br>
edit: paymentid's (or any tx_extra use) can be an issue for fungiubility. I would like to see xmr transactions as similar as possible.
<br>
"
<br>
<br>
Using the luigi1111 website (thank you luigi1111 for llcoins.net!), I determined the public address which is "47WqpxL1yru9nhd6Fyr2daMUqKq9ivLqvBfbGFmwfovnYeeRhikEZLuFuMkpfvarzxTH4ucoFvikpWJNipPM2CWoM8Kjipj" 
<br>
<br>
See more info https://twitter.com/burnssos/status/1000953437880799235
<br>
https://xmr.llcoins.net/addresstests.html
<br>
<br>
Further testing will be conducted when bulletproofs are on the mainnet.
<br>
UPDATE: BULLETPROOFS are awesome in their reduction of tx bloat. (Mixin has even increased).
<br>
Compare:
<br>
https://moneroblocks.info/search/8e420d4ef5ec550c289990a6881307a78e4ab441dccb4cbbb0dda8bb6ef18b5d
<br>
