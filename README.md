# Task_4 Firewall Configuration

## 🔍 Objective
Configure and test basic firewall rules to allow or block traffic on the system.

## 🛠 Tools Used
- UFW (Uncomplicated Firewall)
- Overleaf
- Linux, Windows (OS)

## 🧪 Steps Performed
1. Installed UFW using **sudo apt install ufw**
2. Setup a rule for denying incoming telnet(port 23) traffic on the system
3. Remote connection from another system through port 23
4. Setup another rule for allowing incoming ssh(port 22) traffic on the system
5. Remote connection from another system through port 22
6. Reset the UFW

## 📊 Output
- Incoming telnet connection is blocked to the system when a deny rule is applied on the firewall.
- SSH connection was successful when port 22 was enabled on the firewall.
- Exchanged information between systems using SSH

  ## 🧠 Learnings

  Ufw -help

  
|   COMMANDS             |  DESCRIPTION                                      |
|------------------------|---------------------------------------------------|
|  enable                |  enables the firewall                             |
|  disable               | disables the firewall                             |
|  default ARG           |  set default policy                               | 
|  logging LEVEL         |  set logging to LEVEL                             |   
|  allow ARGS            |  add allow rule                                   | 
|  deny ARGS             |  add deny rule                                    |
|  reject ARGS           |  add reject rule                                  |      
|  limit ARGS            |  add limit rule                                   | 
|  delete RULE|NUM       |  delete RULE                                      |    
|  insert NUM RULE       |  insert RULE at NUM                               |
|  prepend RULE          |  prepend rule                                     |
|  route RULE            |  add route rule                                   |
|  route delete RULE|NUM |  delete route RULE                                |
|  route insert NUM RULE |  insert route RULE at NUM                         |
|  reload                |  reload firewall                                  |
|  reset                 |  reset firewall                                   |
|  status                |  show firewall status                             |
|  status numbered       |  show firewall status as a numbered list of RULES |
|  status verbose        |  show verbose firewall status                     |
|  show ARG              |  show firewall report                             |
|  version               |  display version information                      |
  
