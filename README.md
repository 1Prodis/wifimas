# wifimas
[![Version-shield]](https://raw.githubusercontent.com/1Prodis/wifimas/master/CHANGELOG.md) [![Bash4.2-shield]](http://tldp.org/LDP/abs/html/bashver4.html#AEN21220) [![License-shield]](https://raw.githubusercontent.com/1Prodis/wifimas/master/LICENSE.md) [![Docker-shield]](https://hub.docker.com/r/1Prodis/wifimas/) [![Telegram-shield]](https://t.me/masterhackteam) [![Forum-shield]](https://masterhackteam.com)




> This is a multi-use bash script for Linux systems to audit wireless networks.



---

All the needed info about how to "install | use | enjoy" `wifimas` is present at [Github's Wiki].

- *I. Content & Features*
  - [Home]
  - [Features]
  - [Screenshots]
  - [Wallpapers]


- *II. Requirements*
  - [Requirements]
  - [Compatibility]
	 - [Cards and Chipsets]
	 - [Wayland]
	 - [Consistent Network Device Naming]
	 - [Kali Nethunter]
  - [Essential Tools]
  - [Optional Tools]
	 - [BeEF Tips]
	 - [Hashcat Tips]
	 - [Bettercap Tips]
  - [Update Tools]
  - [Internal Tools]
  - [Known incompatibilities]


- *III. Getting started*
  - [Installation & Usage]
  - [Options]
  - [Docker]
	 - [Linux]
	 - [Mac OSX]
	 - [Windows]
  - [Other Sources]
  - [FAQ & Troubleshooting]


- *IV. Learning*
  - [CWP Certification]


- *V. Project & Development*
  - [Plugins system]
	 - [Plugins development]
	 - [Plugins Hall of Fame]
  - [Supported Languages]
  - [Contributing & Code of Conduct]
  - [Merchandising Online Shop]
  - [Changelog]
  - [Disclaimer & License]
  - [Contact]


- *VI. Acknowledgments & References*
  - [Hat Tip To]
  - [Inspiration]

---

[Banner]: https://raw.githubusercontent.com/1Prodis/wifimas/master/imgs/banners/wifimas_banner.png "We will conquer the earth!!"
[Github's Wiki]: https://github.com/1Prodis/wifimas/wiki

[Home]: https://github.com/1Prodis/wifimas/wiki
[Features]: https://github.com/1Prodis/wifimas/wiki/Features
[Screenshots]: https://github.com/1Prodis/wifimas/wiki/Screenshots
[Wallpapers]: https://github.com/1Prodis/wifimas/wiki/Wallpapers
[Requirements]: https://github.com/1Prodis/wifimas/wiki/Requirements
[Compatibility]: https://github.com/1Prodis/wifimas/wiki/Compatibility
[Cards and Chipsets]: https://github.com/1Prodis/wifimas/wiki/Cards%20and%20Chipsets
[Wayland]: https://github.com/1Prodis/wifimas/wiki/Wayland
[Consistent Network Device Naming]: https://github.com/1Prodis/wifimas/wiki/Consistent%20Network%20Device%20Naming
[Kali Nethunter]: https://github.com/1Prodis/wifimas/wiki/Kali%20Nethunter
[Essential Tools]: https://github.com/1Prodis/wifimas/wiki/Essential%20Tools
[Optional Tools]: https://github.com/1Prodis/wifimas/wiki/Optional%20Tools
[BeEF Tips]: https://github.com/1Prodis/wifimas/wiki/BeEF%20Tips
[Hashcat Tips]: https://github.com/1Prodis/wifimas/wiki/Hashcat%20Tips
[Bettercap Tips]: https://github.com/1Prodis/wifimas/wiki/Bettercap%20Tips
[Update Tools]: https://github.com/1Prodis/wifimas/wiki/Update%20Tools
[Internal Tools]: https://github.com/1Prodis/wifimas/wiki/Internal%20Tools
[Known incompatibilities]: https://github.com/1Prodis/wifimas/wiki/Known%20incompatibilities
[Installation & Usage]: https://github.com/1Prodis/wifimas/wiki/Installation%20&%20Usage
[Options]: https://github.com/1Prodis/wifimas/wiki/Options
[Docker]: https://github.com/1Prodis/wifimas/wiki/Docker
[Linux]: https://github.com/1Prodis/wifimas/wiki/Docker%20Linux
[Mac OSX]: https://github.com/1Prodis/wifimas/wiki/Docker%20Mac%20OSX
[Windows]: https://github.com/1Prodis/wifimas/wiki/Docker%20Windows
[Other Sources]: https://github.com/1Prodis/wifimas/wiki/Other%20Sources
[FAQ & Troubleshooting]: https://github.com/1Prodis/wifimas/wiki/FAQ%20&%20Troubleshooting
[CWP Certification]: https://github.com/1Prodis/wifimas/wiki/CWP%20Certification
[Plugins system]: https://github.com/1Prodis/wifimas/wiki/Plugins%20System
[Plugins development]: https://github.com/1Prodis/wifimas/wiki/Plugins%20Development
[Plugins Hall of Fame]: https://github.com/1Prodis/wifimas/wiki/Plugins%20Hall%20of%20Fame
[Supported Languages]: https://github.com/1Prodis/wifimas/wiki/Supported%20Languages
[Contributing & Code of Conduct]: https://github.com/1Prodis/wifimas/wiki/Contributing-&-Code-of-Conduct
[Merchandising Online Shop]: https://wifimas.creator-spring.com/
[Changelog]: https://github.com/1Prodis/wifimas/wiki/Changelog
[Disclaimer & License]: https://github.com/1Prodis/wifimas/wiki/Disclaimer%20&%20License
[Contact]: https://github.com/1Prodis/wifimas/wiki/Contact
[Hat Tip To]: https://github.com/1Prodis/wifimas/wiki/Hat%20Tip%20To
[Inspiration]: https://github.com/1Prodis/wifimas/wiki/Inspiration

[Version-shield]: https://img.shields.io/badge/version-11.40-blue.svg?style=flat-square&colorA=273133&colorB=0093ee "Latest version"
[Bash4.2-shield]: https://img.shields.io/badge/bash-4.2%2B-blue.svg?style=flat-square&colorA=273133&colorB=00db00 "Bash 4.2 or later"
[License-shield]: https://img.shields.io/badge/license-GPL%20v3%2B-blue.svg?style=flat-square&colorA=273133&colorB=bd0000 "GPL v3+"
[Docker-shield]: https://img.shields.io/docker/automated/1Prodis/wifimas.svg?style=flat-square&colorA=273133&colorB=a9a9a9 "Docker rules!"
[Discord-shield]: https://img.shields.io/discord/629812069964840991.svg?style=flat-square&colorA=273133&colorB=CBA317&logo=discord&label=Discord%20chat
[Paypal-shield]: https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square&colorA=273133&colorB=b008bb "Paypal"
[Cryptocurrencies-shield]: https://img.shields.io/badge/donate-cryptocurrencies-blue.svg?style=flat-square&colorA=273133&colorB=f7931a "Cryptocurrencies"
