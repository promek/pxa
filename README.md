# pxa

Practical Command Execution For Ava v0.1

**install script on linux**
```
$ git clone https://github.com/promek/pxa.git
$ cd pxa
$ chmod +x pxa
```

**Type the command and press enter to see usage.**
```
$ ./pxa PRESS_ENTER

Usage: pxa COMMAND_FILE

Available command files : 

  admin
  avm
  health
  keystore
  platform

Practical Command Execution For Ava v0.1
https://github.com/promek/pxa
```
**Let's see the usage of the commands here.**

```
$ ./pxa admin PRESS_ENTER

Usage: pxa admin ITEM [PARAMS]

 getNodeID) Get the ID of this node.                                          
    Usage: ./pxa admin getNodeID
    
 peers) Get description of peer connections.                                  
    Usage: ./pxa admin peers
    
 getNetworkID) Get the ID of the network this node is participating in.       
    Usage: ./pxa admin getNetworkID

Practical Command Execution For Ava v0.1
https://github.com/promek/pxa
```

**Finally, We can use the commands**
```
$ ./pxa admin getNodeID
{"jsonrpc":"2.0","result":"nodeID":"5mb46qkSBj81k9g9e4VFjGGSbaaSLFRzD"},"id":1}
```

---

## Create a new file for the new commands you want. Write your new commands into that file. it's that easy ...



