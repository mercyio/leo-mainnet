# Leo helloworld (First workshop)

## Run Guide 

Make sure you have Leo installed on your machine. If not, follow the installation instructions provided in the Leo documentation.

Navigate to the directory where your Leo project is located.

run the Leo program using the command:
```bash
leo run <main> <3u32 2u32>
```
Here, <main> represents the transition function name in the Leo program, and 3u32 2u32 are the input parameters for that function.
3u32 and 2u32 specify that the inputs are 32-bit unsigned integers with values 3 and 2.

After running the program, Leo compiles your code and executes the transition function with the provided inputs.
The result of the execution is displayed in the terminal.

Leo generated a file named main.aleo which contains the Aleo instructions corresponding to your Leo program.
This file is essential as it holds the compiled version of your program, ready for deployment on the Aleo network.

#Deployment Process:
I copied the code from the main.aleo file.
This code contains the compiled Aleo instructions required for deployment.

I then navigated to the demo.leo.app/deploy platform.
On this platform, I used the copied code to deploy MY Leo program to the Aleo network.

On the deployment platform, I followed the necessary steps to submit the deployment transaction.
Once deployed, the network would have generated a unique transaction ID, confirming the successful deployment.

TransactionId: 	at1cc7zh43zs3w0st2z59wp2pmlcg50m69dcz3w3z642zdenm6w2crsjttcue


## Simple_token (Second workshop)

Use the following command to run the mint transition function:
```bash
leo run mint aleo129ka6zrvs25rc52qxt9n3299rdsmy4ecx2u9ewfu8a0s5w673v9sucj5km
```
After running the program, Leo compiles your code and executes the transition function with the provided inputs.
The result of the execution is displayed in the terminal.

Leo generated a file named main.aleo which contains the Aleo instructions corresponding to your Leo program.
This file is essential as it holds the compiled version of your program, ready for deployment on the Aleo network.

#Deployment Process:
I copied the code from the main.aleo file.
This code contains the compiled Aleo instructions required for deployment.

I then navigated to the demo.leo.app/deploy platform.
On this platform, I used the copied code to deploy my Leo program to the Aleo network.

On the deployment platform, I followed the necessary steps to submit the deployment transaction.
Once deployed, the network would have generated a unique transaction ID, confirming the successful deployment.

TransactionId: 	at1xkhrcxcwh8a674gwk6ernx4c43wf2a77rm9twk97rfru5s3g8uysv5h4gu

## Token transfer (Third workshop )

Use the following command to run the combine_hash_owner_receiver transition function:
```bash
leo run combine_hash_owner_receiver <owners leo wallet address> <receiver leo wallet address>
```
You need two Leo wallet addresses: one for the owner and one for the receiver. Replace <owners leo wallet address> and <receiver leo wallet address> with the appropriate addresses you intend to use.

After running the command, check the output in your terminal for any results or messages related to the execution of the combine_hash_owner_receiver function.
The result of the execution is displayed in the terminal.

Leo generated a file named main.aleo which contains the Aleo instructions corresponding to your Leo program.
This file is essential as it holds the compiled version of your program, ready for deployment on the Aleo network.

#Deployment Process:
I copied the code from the main.aleo file.
This code contains the compiled Aleo instructions required for deployment.

I then navigated to the demo.leo.app/deploy platform.
On this platform, I used the copied code to deploy my Leo program to the Aleo network.

On the deployment platform, I followed the necessary steps to submit the deployment transaction.
Once deployed, the network would have generated a unique transaction ID, confirming the successful deployment.

TransactionId: 	at1nccf0xje0n7dltjf9lv3p3rjtjysz0qps0dfh6zvsrcvuz6dzc8qwmhmpz

<!-- 
## Summary
The 3 workshop ran and was deployed successfully with transactionId generated for each. -->
