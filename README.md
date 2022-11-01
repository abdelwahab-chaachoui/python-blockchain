# python-blockchain
a small blockchain with a low consens mechanism implementation

## what is needed?
- Server
    here the server is the blockchain itself
    it s a linked list 
      - can be saved in memory (for test purposes)
      - can be saved externally (advanced)
    this linked list is built with multiple blocks
      - each block has a hash pointer
        - found through the work of nodes
        - and with help of Consens mechanism for the hash to be found
        - need hash function
      block contains
        - blocktime
        - data (transactions)
        - timestamp
        - nonce
      
      
- Client
     client should be able to connect to the blockchain
        - can be connected as 
            - consens finding node
            - simple node
- UI
    here a simple explorer of our blockchain
    show multiple blocks 
    access blocks by their hash
    maybe add an adress finder
