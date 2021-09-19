## Introduction
In this first tutorial we roughly follow the tutorial in (https://blog.openzeppelin.com/the-hitchhikers-guide-to-smart-contracts-in-ethereum-848f08001f05/)

1. To simulate a blockchain type from the command prompt type ```truffle develop```. 
	- Take note of which port is being used by the app. 
	- We leave this app running in the background.
2. Start a new prompt, in a new folder type ```truffle init```. 
	- This will create a new folder with all the files needed to run Truffle.
3. Edit the file ```truffle-config.json```
	- Enable ```development``` in ```networks``` and make sure the ```port``` field matches the port in step (1)
4. To check that everything works type:
	- ```truffle compile``` to compile the contracts in the ```contracts/``` folder
	- ```truffle migrate``` to register the contracts in the chain 
