# vemer-adr-r-esphome
ESPHome Yaml for getting readings from a Vemer ADR-R energy meter through RS485 interface.

What I wanted to do, is get my Vemer ADR-R readings, into Home Assistant, wirelessly without the use of ADRView software.
Vemer was really helpful to give all the information needed concerning modbus communication, including all the necessarey addresses.
So with a bit of try and error method, I finally got the readings to appear in Homeassistant and I thought to share the code.
What ESPHome documentation doesn't state, or I didn't personally find it, is the fact that addresses have to be expressed in a hexademical format.
So it was a big headache to figure why, even if I had all the addresses right, I only got communication errors.
Luckily, I guessed what was going on and I figured it out.

So, to help me with my headache, if you found this stuff useful, feel free to buy me some beer or some DEPON pills, donating something in the link below :)

[Make a donation through Paypal](https://www.paypal.com/donate/?hosted_button_id=TJHU3Q3FDJZAG)

If anyone, ever, donates more than 5 EUR which is the value of a good glass of beer, the money will be given to charity to help children.
