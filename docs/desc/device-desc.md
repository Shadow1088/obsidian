parent: [[client]]
child: [[device-hw]]

purpose:
- send data

visual:
- as little as possible

powered by:
- battery

telecommunications:
- celluar (4G , NB-IoT) - [1NCE](https://www.1nce.com/en-eu/1nce-connect/pricing)

modes:
- off
- passive-on (every #x minutes executes #Share) (eDRX for power saving) #TODO 
- active-on (executes #Emergency and every #x seconds executes #Share) #TODO 
- setup (starts AdHoc network and opens a config website, *auth*) 

**Key features:**
- #Share: shares location to the overseers
- #Emergency: sends HELP signal to the overseers
	HELP signal purposely wakes up overseers *even if active* and activates #Share feature



