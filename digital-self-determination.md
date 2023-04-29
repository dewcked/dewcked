I hope people should be aware of how their data is treated. So I'm writing my opinion about [digital self determination](https://en.wikipedia.org/wiki/Digital_self-determination).

Humans generate data everytime. Even if you don't think you are, you are generating data. Data could be your fingerprint, hair, face captured by CCTVs, web cookies, address, gender, writings, etc..

Admit humans cannot fully controll every data they generate in normal situations. If you think you can, you only stay within your room.

For non-digital information, it is not that hard to erase or not that critical privacy leak. You want to erase fingerprint after door-lock authentication, then rub after authentication. Hair is not that critical privacy leak as it is almost impossible to match the hair with yours.

For digital information, it is very hard to avoid privacy leak. And it is almost impossible to erase leaked privacy data. This is why **digital self determination** is important concept and why people should aware of how their data is collected, analyzed, processed, stored, deleted, vendored and sold.

Here is my simple rule for **digital self determination**


1. Use VPN. Any trusted VPN is ok. I use protonVPN.
  - If you need to use voice-chat like thingy, VPN might be slow enough to break the functionality. Then determine when to turn off your VPN.
2. Disable all kinds of telemetry thingy
  - Search internet. Disable telemetry functions in OSs(Windows, Android, ...), Browsers(Edge (Never use chrome itself), Firefox), ...
3. Filter network traffic. In Android, use NoRoot Firewall and allow only whitelisted application. It improves privacy. Oh, deleting google play store is good. But if you have to download apps from there, use Aurora Store. It is not perfect, but better.
  - I hate Apple As much as I hate Google. Some say Apple provides best privacy experience, [I doubt that](https://www.washingtonpost.com/technology/2020/12/29/lens-technology-apple-uighur/). So, you still want to Apple products?
4. Web extensions
  - I use Ublock Origin and whitelist websites.
  - If you want to whitelist a website then add the rule below
5. Use private mail. Any trusted mail is ok. I use mailfence, protonmail, tutanota.
  - Determine which mail to use in which purpose. For shopping? work?
  - Use temporary mail if possible an if you don't need to put your private information in there

`@@||websiteyouwanttowhitelist^$1p`

`1p` means first-party, `3p` means third-party, `all` means everything

Find more at [https://github.com/gorhill/uBlock/wiki/Static-filter-syntax
](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#extended-syntax)

You are kinda safe now! Good to go.

