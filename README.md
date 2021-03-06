<a href="http://openbazaar.org"><img src="http://s27.postimg.org/5i0igk0v7/Open_Bazaar_Logo.png" width="800px"/></a>

[![Build Status](https://travis-ci.org/OpenBazaar/OpenBazaar.svg?branch=master)](https://travis-ci.org/OpenBazaar/OpenBazaar)
[![Dev Build Status](https://travis-ci.org/OpenBazaar/OpenBazaar.svg?branch=develop)](https://travis-ci.org/OpenBazaar/OpenBazaar)
[![Coverage Status](https://coveralls.io/repos/OpenBazaar/OpenBazaar/badge.png)](https://coveralls.io/r/OpenBazaar/OpenBazaar)
[![Stories in Ready](https://badge.waffle.io/OpenBazaar/OpenBazaar.svg?label=ready&title=Ready)](http://waffle.io/OpenBazaar/OpenBazaar)
[![Slack Status](https://openbazaar-slackin-drwasho.herokuapp.com/badge.svg)](https://openbazaar-slackin-drwasho.herokuapp.com)

======

Let's make trade **free**.

**OpenBazaar** is a decentralized peer-to-peer marketplace where goods and services are traded in Bitcoin. OpenBazaar uses a Kademlia-style distributed hash table (DHT), which is architecturally comparable to BitTorrent. Items are created and hosted on the nodes of users on the network. The project is originally based off of the proof of concept code for DarkMarket, created by Amir Taaki and Airbitz, and is now licensed under the [MIT license](http://opensource.org/licenses/MIT).

- **Official Site:** https://openbazaar.org
- **Contact us:** project@openbazaar.org
- **Slack:** https://openbazaar-slackin-drwasho.herokuapp.com
- **IRC Chat:** #OpenBazaar on [Freenode](https://webchat.freenode.net/)
- **Forums:**
  - *unSYSTEM*: https://forum.unsystem.net/category/projects/openbazaar
  - *Bitcoin Talk*: https://bitcointalk.org/index.php?topic=768081.0
- **Original Presentation at Toronto Hackathon:** https://www.youtube.com/watch?v=lHVqH8XO1Pk#t=86
- **Slides from 'Bitcoin in the Beltway' by Brian Hoffman:** http://www.slideshare.net/openbazaar/open-bazaar

## Support
You can financially support the project by either:

1. A direct donation: [3MXYUBLWNETa5HTewZp1xMTt7AW9kbFNqs](https://blockchain.info/address/3MXYUBLWNETa5HTewZp1xMTt7AW9kbFNqs)
2. Tip4Commit: https://tip4commit.com/projects/728
  - Code committed to the project is rewarded with bitcoin: [![tip for next commit](https://tip4commit.com/projects/728.svg)](https://tip4commit.com/github/OpenBazaar/OpenBazaar)

## Features (Notional)
- Full market editor for management of items catalog
- Order management system
- Ricardian contracts
- Multisignature escrow-based transactions
- Notary and dispute resolution marketplace
- Private messaging
- Identity/Reputation system

## Project Status
- *OpenBazaar* is currently in **Beta 5.0**
- New versions are scheduled for release at the end of each month
- [Development Roadmap](https://github.com/OpenBazaar/OpenBazaar/wiki/03.-Development-Roadmap)

## Build Instructions

For Linux and OSX users, run these commands:

```
git clone https://github.com/OpenBazaar/OpenBazaar.git

cd OpenBazaar

./configure.sh
```

After running the configure.sh script you should have an OpenBazaar installation ready to go, to start run: 
```
./openbazaar start
```
OpenBazaar will open in a random port on your default web browser. Note that it may take several minutes for OpenBazaar to completely start.

Read more on [build instructions in our wiki](https://github.com/OpenBazaar/OpenBazaar/wiki/01.-Getting-Started).

## Artwork Contributions
<img src="https://blog.openbazaar.org/wp-content/uploads/2014/07/logo.png" width="500px"/>  
contributed by Jacob Payne  
<img src="https://i.imgur.com/WwPUXGS.png" width="500px"/>  
contributed by Dean Masley

## Theory Work
1. [Ricardian Contracts](https://gist.github.com/drwasho/a5380544c170bdbbbad8) by Dr Washington Sanchez
2. [P2P Lending on OpenBazaar](https://gist.github.com/drwasho/2c40b91e169f55988618) by Dr Washington Sanchez
3. [Auctions on OpenBazaar](https://gist.github.com/drwasho/d923d2d37f544ea22e6f) by Dr Washington Sanchez
4. [Services on OpenBazaar](https://gist.github.com/drwasho/632d126a4189467c1280) by Dr Washington Sanchez
5. [The Issuance and P2P Transfer of Shares on OpenBazaar](https://gist.github.com/drwasho/3670bb1c59e620fffb24) by Dr Washington Sanchez and Delain Markos
6. [Voting Pools in OpenBazaar](https://gist.github.com/drwasho/c04f16fcc7be9a666e90) by Dr Washington Sanchez
7. [Distributed Currency Exchange](https://gist.github.com/drwasho/aa6ab79e92f2a876073e) by Dr Washington Sanchez
8. [OpenBazaar Genesis Contract](https://gist.github.com/drwasho/76e1161db1e5b860598a) by Dr Washington Sanchez (arbiter), Brian Hoffman (buyer), and Samuel Patterson (seller)
9. [A pseudonymous trust system for a decentralized anonymous marketplace](https://gist.github.com/dionyziz/e3b296861175e0ebea4b) by Dionysis Zindros
10. [Dispute Resolution in OpenBazaar - Arbitration Market](https://gist.github.com/drwasho/405d51bd1b1a32e38145) by Dr Washington Sanchez
11. [Notary Selection in OpenBazaar](https://gist.github.com/drwasho/a0225f5455e508095ac2) by Dr Washington Sanchez
12. [Risk and Insurance in OpenBazaar](https://gist.github.com/drwasho/9759924342859872851e) by Dr Washington Sanchez
13. [Subspace and OpenBazaar](https://gist.github.com/drwasho/8daf0e95d42ab2266e6b) by Dr Washington Sanchez
14. [Bounded Futures Contracts: Hedging Against Price Volatility](https://gist.github.com/drwasho/04dbaf19da4f4a8ae512) by Dr Joseph Clark and Dr Washington Sanchez

## Screenshots
Here are some screenshots of the *alpha* UI so far:

![Screen 1](http://s30.postimg.org/6kmmyhs01/Screen_1.png)
![Screen 2](http://s30.postimg.org/mf1j8dgqp/Screen_2.png)
![Screen 3](http://s30.postimg.org/k2tjas45d/Screen_3.png)
![Screen 4](http://s30.postimg.org/94i9slfk1/Screen_4.png)
![Screen 5](http://s30.postimg.org/fr4xlrx8h/Screen_5.png)
![Screen 6](http://s30.postimg.org/40r04e4g1/Screen_6.png)
![Screen 7](http://s30.postimg.org/fkr8ioo3l/Screen_7.png)
![Screen 8](http://s30.postimg.org/fw8ovg4jl/Screen_8.png)

## License

OpenBazaar is licensed under the MIT license. See [LICENSE.md](LICENSE.md) for more information.
