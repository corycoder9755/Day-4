# Elevated Labs Internship Solutions

# Task 1
## Opening Firewall Configuration Tool(UFW)
![Tool snapshot](Media/ufw_panel.png)

# Task 2
## List Current Firewall Rules
Command : ```sudo ufw numbered```
![Tool current status snapshot](Media/ufw_current_status_starting.png)

# Task 3
## Adding Inbound Rule Port 23
Command : ```sudo ufw deny 23```
![snapshot ufw deny 23](Media/ufw_deny_23.png)

# Task 4
## Test the rule by connecting
command : ```telnet {ip_of_machine}```
![snapshot of telnet connection](Media/telnet_deny_screenshot.png)

# Task 5
## Allow Port 22 (SSH)
command : ```sudo ufw allow 22```
![snapshot allow ssh](Media/ufw_allow_22.png)

# Task 6
## Remove test block rule
command : ```sudo ufw reset```
![snapshot remove block](Media/ufw_reset.png)

# Task 7
## How does Firewall Filters Traffic
Firewall Works by Checking the Incoming Packet Header and match that based on predefined rules, If the rule says allow then only it will allow the packet into the Network if not then it will block the packet thus providing security
