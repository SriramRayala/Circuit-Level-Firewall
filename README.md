# CIRCUIT-LEVEL FIREWALL
### Introduction
Circuit-level firewalls function similarly to application gateways in that they too use a proxy to secure the network. When the circuit gateway scans a packet, however, it often only checks that the connection is legitimate, ensuring that the incoming packets are coming from the same source that the request was sent to and that the user has sufficient privileges for whatever service is needed.
Circuit-level gateways offer a wider variety of possible rules than other firewalls along with its proxy service, so it is more versatile in this regard. For example, it can block specific URLs from being accessed, whereas a packet filter would need the IP address of the website, which may not be unique since many large companies such as Google use multiple servers.

Elaborating this we are using the URL blocking approach of Circuit-Level Firewall.

#### Packages used
1. [time](https://docs.python.org/3/library/time.html)
2. [datetime](https://docs.python.org/3/library/datetime.html)
3. [tqdm](https://pypi.org/project/tqdm/)

P.S.: No special commands are needed to install these packages as they already exist in Python.

### OS and Commands
##### OS
This code is made to run the file on Kali Linux but yes you can run it on any other os as well. Just you need to change the 'host_path'.
For checking the hosts path click below as per prefered OS: 
1. [Windows](https://us.battle.net/support/en/article/31364)
2. [Mac](https://www.nexcess.net/help/how-to-find-the-hosts-file-on-my-mac/#:~:text=Hosts%20File%20Location%20on%20Macs&text=The%20Hosts%20file%20on%20a,the%20%2Fetc%2Fhosts%20folder.)

##### Commands
Make sure you are in root environment for Kali Linux or running as an administrator in Windows OS.
1. **sudo su** (For enabling root)
2. **cd {Your Circuit Level Firewall file location}** (To change the directory)
3. **python3 circuit-level-firewall.py**
