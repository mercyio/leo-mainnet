# leo-testnet

The bootcamp was created on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust.

## Workshop 1

Transaction ID: at1cc7zh43zs3w0st2z59wp2pmlcg50m69dcz3w3z642zdenm6w2crsjttcue

### Steps
1. Install rust on your pc
2. clone the leo repo from their official github page
3. `cd leo`
4. `cargo install --path .` to install the dependencies
5. `leo new todolist`
6. Note: the name of your project must be in lowercase
7. `cd todolist`
8. change the PRIVATE_KEY in your .env file to yours
9. `leo run`
10. `leo deploy`

![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(64).png?raw=true)


## Workshop 2

Transaction ID: at1xkhrcxcwh8a674gwk6ernx4c43wf2a77rm9twk97rfru5s3g8uysv5h4gu

### Steps
1. Install rust on your pc
2. clone the leo repo from their official github page
3. `cd leo`
4. `cargo install --path .` to install the dependencies
5. `leo new newproject`
6. Note: the name of your project must be in lowercase
7. `cd newproject`
8. change the PRIVATE_KEY in your .env file to yours
9. `leo run mint yourwalletaddress 1000u64 --network testnet`
10. `leo run transfer "token" youraddress 100u64 --network testnet`
11. `leo deploy`

![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(65).png?raw=true)
![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(66).png?raw=true)

## Workshop 3

Transaction ID: at1nccf0xje0n7dltjf9lv3p3rjtjysz0qps0dfh6zvsrcvuz6dzc8qwmhmpz

### Steps
1. Install rust on your pc
2. clone the leo repo from their official github page
3. `cd leo`
4. `cargo install --path .` to install the dependencies
5. `leo new newproject`
6. Note: the name of your project must be in lowercase
7. `cd newproject`
8. change the PRIVATE_KEY in your .env file to yours
9. `leo run combine_hash_owner_reciever youraddress party2address`
10. `leo run`
11. `leo deploy`

![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(67).png?raw=true)
![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(68).png?raw=true)
![alt text](https://github.com/Aikay-dev/leo-testnet/blob/main/Screenshot%20(69).png?raw=true)

