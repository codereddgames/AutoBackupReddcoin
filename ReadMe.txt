This program is a simple application that allows a user to set up auto backup features for their Reddcoin wallet...

1. Make sure your wallet is set up to run RPC commands.  
	a. If you haven't got a reddcoin.conf file, create a blank text document and enter the following:
		rpcuser=SomeUserNameOfYourChoice
		rpcpassword=SomeCrazyPasswordOfYourChoice
		rpcport=45443
		rpcallowip=127.0.0.1
		server=1
	   and save it as reddcoin.conf

	b. Open your Reddcoin folder where the wallet.dat file is located and drop in your reddcoin.conf file.  Restart wallet.  
	   For Windows, it's generally here: C\Users\<username>\AppData\Roaming\Reddcoin

2. In the folder where this program is located, you will see a config.conf file.  It has basic data filled out.  Just fill in your RPC username and password
   and locations within which you wish to keep your backups

3. Run the program.

If you want to schedule backups, click on your start menu.  Search for Task Scheduler.  Follow the instructions on creating a simple task. 

Donations can be made to Rh2tJ93bTR277kqwqSQCpBcukznuUTiS1N