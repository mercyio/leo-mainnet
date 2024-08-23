# leo-testnet

The bootcamp was created on Coin Ex and Aleo to introduce developer to Leo Programming Language which is built on Rust.

## Workshop 1

Transaction ID: at1yraaea42e2quy55m97g5t45grctfxs7a40fet8el9w5dr0wxrvgskuq3cl

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

Transaction ID: at12zyxve7mpgdk4aghnt9h933x2dwd7hs5p9kgkjmrvq80dlacsvgqla6ele

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

Transaction ID: at1mkes8qqq25etyadu4s2pkga43q3vr7xhx3v5l7vqww26ne74gc8qwuwa97

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

