# Gekkoscience-cgminer
cgminer for Gekkoscience Miners

Usage:

First run the AutoInstaller to compile and install cgminer.

	$ ./RPi-AutoInstaller

Wait for the AutoInstaller to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First, choose a name for the bash script to be saved as, no spaces allowed.

	   Save As:
	 $ Exampe

Second, Insert chosen scrypt pool url.

	  Pool URL:
	$ stratum+tcp://jp.stratum.slushpool.com:3333

Third, Insert worker name for selected pool.

	  Pool Worker:
	$ meap10.test

Forth, Insert worker password.

	  Worker Password:
	$ x

Fifth, Select type of Gekkoscience Miner

	  Miner Type:
	  2pac or newpac
	$ 2pac

Sixth, Choose Frequency for Miner, cooling is recommended for anything past 100!

	  Miner Frequency:
	  Can be 100, 125, 150, 175, 200
	  **Use cooling for anything passed 100!**
	$ 100

Seventh, Now you can Insert any extra arguments for cgminer, If none just hit enter.

	  Extra Arguments For cgminer:
	  Example: --suggest-diff 32
	  **If none hit Enter**
	$ 

Once that's done, run the script just made with a ./ infront of the name.

	$ ./Example  

If all is done well, you should see something like this.

	  cgminer version 4.11.1 - Started: [2021-08-29 06:13:59.604]
	  --------------------------------------------------------------------------------
	  (5s):14.36G (1m):11.45G (5m):8.260G (15m):4.030G (avg):11.54Gh/s
	  A:512  R:8192  HW:0  WU:160.3/m
	  Connected to jp.stratum.slushpool.com diff 512 with stratum as user meap10.test
	  Block: df47aee4...  Diff:17.6T  Started: [06:13:59.606]  Best share: 284
	  --------------------------------------------------------------------------------
	  [U]SB management [P]ool management [S]ettings [D]isplay options [Q]uit
	  0: GSD 10016214: BM1384:2 100.00MHz      | 12.08G / 11.94Gh/s WU:166.9/m
	  --------------------------------------------------------------------------------
	  [2021-08-29 06:13:58.289] Started cgminer 4.11.1
	  [2021-08-29 06:13:58.292] Probing for an alive pool
	  [2021-08-29 06:13:58.625] Pool 0 difficulty changed to 8192
	  [2021-08-29 06:13:58.905] Rejected untracked stratum share from pool 0
	  [2021-08-29 06:13:59.544] GSD 0: 2Pac BM1384 Bitcoin Miner (10016214)
	  [2021-08-29 06:13:59.606] Network diff set to 17.6T
	  [2021-08-29 06:13:59.811] GSD 0: found 2 chip(s)
	  [2021-08-29 06:13:59.871] GSD 0: setting frequency to 100.00MHz
	  [2021-08-29 06:13:59.879] GSD 0: open cores @ 100.00MHz
	  [2021-08-29 06:14:00.528] GSD 0: start work @ 100.00MHz
	  [2021-08-29 06:14:51.153] Pool 0 difficulty changed to 1638
	  [2021-08-29 06:14:51.154] Stratum from pool 0 requested work restart
	  [2021-08-29 06:15:21.158] Pool 0 difficulty changed to 512
	  [2021-08-29 06:15:21.159] Stratum from pool 0 requested work restart

