# SBeacon
Secure Beacon - an elegant solution to protect from Beacon spoofing --- FUNDING NEEDED!!!

## Avant propos
One of the main issues realted to Beacons (iBeacons, AltBeacons etc) is the fact that they are public, open and anyone can spoof them with a mobile phone and a simple appilcation. For more details see: http://makezine.com/2014/01/03/reverse-engineering-the-estimote/ , that includes also communication betweek beacon and phone application hacking.  
It is true that there are a couple of solutions on the market, the worse is Apple's: http://beekn.net/2014/05/apple-closed-system-apple-slowly-locking-ibeacon/ and this proves that nobody is safe from bad or let's be honest stupid technical decissions. But Apple can do whatever they please, they can afford it.

## An elegant technical solution
Our team considers that Beacons and Smart Bluetooth/Bluetooth Low Energy will be the future and those devices will be present everywhere in huge quantities - billions, hundred of billions. In this case it is obvious that you can not keep a list with all registred beacons for a mobile application - we saw the same approach back in the days before Google, with Yahoo lists of lists within lists. In our opinion that model was wrong and we accept the fact that maybe we are wrong and Yahoo is the best way to search the Internet and there is conspiracy against it conducted by Google - if you think this is the case the please close this page and go on another site.  
So, let's explain our approach, our starting premises:
- the interaction between you mobile (the application running on your mobile) and the Beacon is local and very shot. Your application will exchange just a couple of packets with the Beacon and that's all.
- most of the logic is in the application on your phone
- if you change often enough the public apearance of your Beacon it will be pointless to spoof it  

Then we propose the following solution:
- change the public exposure of the Beacon - via an internal software running on the Beacon, in such a way any smart phone running your application will be able to correctly identify your Beacon and compute the information that is associated with it.

In technical terms, the solution consists of:
- hardware: Beacons based on nRF51x SoC
- software running on Beacons allowing you to configure your network
- mobile application able to recognize the Beacons as being part of your network and distingush them from the other active Beacons in range. Also the mobile application will allow Beacon software update and to gather information about internal Beacon status (baterry level, power level, temperature, physical shocks etc)
- web application allowing you to manage the algorithm running on Beacons, your Beacon network and the way you exchange information with partner networks.


## So what ... it's in it for me
You have a secure way to create your own Beacon network - nobody will be able to highjack the information. You may exchange is a safe way information with Beacons from other networks allowing you to merge, exchange and cover a bigger area with the same application.  
If you can visualise this new Beacon network as local classic phone system or like the cable system: you can create one or several local networks and then you are able to interconnect them, merge them and switch from one to the other (roaming principle). As you may notice this is a complete different solution with respect to Apple's closed proposal and other proprietary solutions.  


If you consider that building the future most powerful network is your challenge then join us!







