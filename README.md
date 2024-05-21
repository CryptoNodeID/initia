### Prerequisite :
#### Ensure 'git' and 'build-essential' already installed
    apt-get update -y && apt-get install git build-essential -y
### Steps :
#### Download the release :
    git clone https://github.com/CryptoNodeID/initia.git
#### run setup command : 
    cd initia && chmod ug+x *.sh && ./setup.sh
#### follow the instruction and then run below command to start the node :
    ./start_initiad.sh
#### Claim testnet faucet, fund address in the node and wait until node syncing done then run :
    ./create_validator.sh
### Available helper tools :
    ./start_initiad.sh
    ./stop_initiad.sh
    ./check_log.sh
    
    ./create_validator.sh
    ./unjail_validator.sh
    ./check_validator.sh

    ./claim_commission.sh
    ./delegate.sh

    ./list_keys.sh
    ./check_balance.sh
    ./get_address.sh