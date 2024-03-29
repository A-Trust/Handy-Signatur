# Handy-Signatur

Handy-Signatur is a qualified remote signature which is triggered via signature password and a second authenticating factor (e.g. cellphone).

Phonenumber, signature password and verification TAN must always be entered on A-Trust web pages starting with https://service.a-trust.at/mobile/, https://www.a-trust.at/mobile/.

> Therefore it is not permitted to parse the web page or have it filled in automatically using a program/script. This is stated in the user agreement for mobile signature.

Local applications that utilize Handy-Signatur have to use a local web browser or a browser control to display the A-Trust page.

# adjustment and appearance when using Handy-Signatur as iframe
To integrate Handy-Signatur in a finished webapp, the appearance can be adjusted with the following parameters:
| parameter | description | example |
| --- | --- | --- |
| appletwidth | max width of the input elements | 300 |
| appletheight | max height ofthe input elements | 300 |
| width | *see appletwidth* |
| height | *see appletheight* |
| backgroundcolor | desired color the iframe background should be | yellow |
| redirecttarget | target to redirect to for iframe (when using RedirectURL) | \_parent |
| telephonenumber | predefined phonenumber is passed to iframe | 0676123456789 |
## iframe sizes
The following iframe sizes have been tested explicitly:
- width 300px, height 300px (300x300)
- __width 350px, height 350px (350x350) - recommended size__
- width 450px, height 450px (450x450)

# Signatur-Box
A Signatur-Box can be used for the use of Handy-Signatur in areas with strict compliance guidelines or when multiple documents need to be signed with one signature trigger (batch signature). For more information, see [A-Trust Signatur-Box](https://www.a-trust.at/de/handy-signatur/signaturbox/).

