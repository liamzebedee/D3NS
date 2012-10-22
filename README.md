# D3NS
Dens is an unfinished decentralized DNS solution that runs atop the [XDen](http://github.com/liamzebedee/xden) P2P key-value store.

## Why?
Why is this project important? 3 Reasons:

### #1
*DNS is centralized.*

The Internet is the most powerful tool ever created for **almost** decentralized communication. Almost. DNS is the critical infrastructure that powers the Internet, and coincidentally it is the critical weakness of the Internet's structure. With centralization of DNS, there is possiblity for censorship.

### #2
*This project is viable.*

There exists one useful decentralized DNS solution as of current, which is Namecoin. Unlike .I2P and Tor Hidden Services, Namecoin's domains are arbitrary - foobar.bit as opposed to kpvz3ri2x5abwt55.onion - and they have economic backing via Bitcoin, which guards against spam. The reason no-one likes Namecoin is that it's not amazing enough. It does provide decentralization of domain name storage but the concept is still the same - domains have owners who pay for them thus they know best.

Dens runs atop XDen. XDen provides a mutable key-value store which is moderated by an efficient system based on trust networks. Name squatting is not possible; it is only allowed if the nodes of a system allow it. There is also no economic basis to domains (it is possible to extend the protocol with this). 

### #3 
*This project is unique.*

This project provides an avenue by which concepts such as trust networks can be explored. Without a proof-of-concept work, no-one has found the potential in such things. 

## How to help
All development efforts should be directed towards [XDen](http://github.com/liamzebedee/xden), which is 95% of this project. 
