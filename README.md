# Leo helloworld (First workshop)

## Run Guide 

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


## Execute Guide

To execute this program, run:
```bash
leo execute main
```

## Overview 

This example shows how to sum two u32 numbers.

It takes the input data from inputs/helloworld.in
