# Creating a frontend in React
Now, we are going to create a react app and set up the front-end of the application. In the frontend, we represent token1 and token2 as KAR and KOTHI respectively.

Open a terminal and navigate to the directory where we will create the application.

```text
cd /path/to/directory
```

Now clone this github repository, move into the newly `avalance-amm` directory and install all the dependencies.

```text
git clone https://github.com/realnimish/avalanche-amm.git
cd avalanche-amm
npm install
```

In our react application we keep all the React components in the `src/components` directory.

* **BoxTemplate** :- 
It renders the box containing the input field, its header, and the element on the right of the box, which can be a token name, a button, or is empty.

* **FaucetComponent** :-
 Takes amount of token1 (KAR) and token2 (KOTHI) as input and funds the user address with that much amount.

* **ProvideComponent** :-
Takes amount of one token (KAR or KOTHI) fills in the estimated amount of the other token and helps provide liquidity to the pool.

* **SwapComponent** :- 
Helps swap a token to another. It takes the amount of token in input field *From* and estimates the amount of token in input field *To* and vise versa.

* **WithdrawComponent** :-
Helps withdraw the share one has. Also enables to withdraw to his maximum limit.

* **ContainerComponent** :- 
This component renders the main body of our application which contains the center box containing the tabs to switch between the four components Swap, Provide, Faucet, Withdraw. And also renders the account details and pool details.

Now it's time to run our React app. Use the following command to start the React app.
```text
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to interact with the AMM.
