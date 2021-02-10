<p align="center">
    <ins><b>Blockchain Homework: POA Chain</b><br><ins>
    Introduction: Proof of Authority Development Chain

<ins>Setup Instructions & Dependencies 

For our Proof of Authority Development Chain we first begin by creating a repository/local folder followed by opening a gitbash window (Window Users) and directing into  the file where Blockchain Tools is located. 


After being in the Blockchain Folders, under gitbash, we begin our development chain by creating two accounts using geth, a command line interface for running ethereum nodes, by using the following codes:

- geth --datadir node1 account new

- geth --datadir node2 account new

This will create two public address keys that will be used afterwards in order to begin mining blocks

Below is a representation of the beginning process of creating our development chain.
    <img src=Blockchain_Screenshots/Capture_1.png>
</p><br>

<p>

After we have obtained our account addresses that are serving as our pre-approved sealer addresses, we need to generate our genesis block. Or in simpler terms, the first block in our blockchain. We start by running "puppeth", a blockchain service management tool, that will allow us to name our new network and begin our new genesis block.

Followed by naming our network and beginning our block, we will choose the Proof of Authority consensus algorithm, insert both of our account addresses from the previous steps stated above in order to pre-fund our block. The remaining of the steps must be followed through accordingly, as I will provide a depiction of what exactly needs to go within the configurations. Once this is complete, we can now export our configurations and initialize our new nodes with our genesis' json file. 




<img src=Blockchain_Screenshots/Capture_2.png>
</p><br>


<img src=Blockchain_Screenshots/Capture_3.png>


<img src=Blockchain_Screenshots/Capture_4.png>

<img src=Blockchain_Screenshots/Capture_5.png>


The above are a series of images taken during the process of the final touches of the configurations as well as the initialization of our nodes. After this is complete, our private PoA blockchain can now begin running! 

As both nodes should be up and running, our blockchain should now be connected to our "MyCrypto" wallet 

Once entering MyCrypto, we can set up our chain ID (the same ID we chose while in the process of creating our block), our node name, network name, our URL, and other details required to make sure the wallet is connected appropriately. 


<img src=Blockchain_Screenshots/Capture_6.png>
<img src=Blockchain_Screenshots/Capture_7.png>
<img src=Blockchain_Screenshots/Capture_8.png>



The above images show the completed transaction between our nodes that successfully ran and our "MyCrypto" wallet. There is an image showing the wealthy amount that was successfully mined. Our last image depicts the status as successful as well as our block number, our to and from node addresses and our amount transferred. 