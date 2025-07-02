# honeypot
I set up a simple honeypot using Pentbox, a lightweight security tool included in Kali Linux. Pentbox allows the creation of basic TCP honeypots to monitor and log unauthorized connection attempts.

Steps taken:

.Launched Pentbox from terminal 

.Navigated to the Honeypot section in the Pentbox menu.

.Selected the TCP Honeypot option.

.Configured the port (e.g., port 23 to simulate a Telnet service).

.Enabled logging to capture attacker IP addresses and connection attempts.

Purpose:
The honeypot was designed to simulate a vulnerable service and attract potential attackers, helping me monitor unauthorized access attempts and study their behavior.

Outcome:
The honeypot successfully logged connection attempts, showing IP addresses and timestamps of devices trying to interact with the fake service.

The code:
- wget http://downloads.sourceforge.net/project/pentbox18realised/pentbox-1.8.tar.gz
- tar xvfz pentbox -1.8.tax.gz
- cd pentbox-1.8/
- ./pentbox.rb
- 2
- 3
- 1
