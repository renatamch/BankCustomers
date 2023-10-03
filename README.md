# BankCustomers
Context: I was asked to personalize the interactions with the customers of a Bank.  
Goal: Use generative AI to create personalized marketing messages that will be delivered to each customer.

I) I received a file .csv (BankCustomersIdFile.csv) with users IDs.  
II) Extracting users data from the BankCustomersIdFile.csv file: 

  ![image](https://github.com/renatamch/BankCustomers/assets/136348810/2467a1d5-1b79-422d-ba2d-6f7a449f07ed)

III) Getting the data for each ID using the API = https://sdw-2023-prd.up.railway.app

![image](https://github.com/renatamch/BankCustomers/assets/136348810/b2fc4fba-339f-40d7-a703-9a4328e962f3)

IV) Transforming the data using the OpenAI GPT-3.5-turbo API to generate a personalized marketing message for each user.

  ![image](https://github.com/renatamch/BankCustomers/assets/136348810/dac5246f-f319-44b7-96b7-be81aae00267)

Prompts for first run: 

Secure your future with smart investments!
Secure your future with smart investments! Start growing your wealth today, Mariana.
Investing today secures your future! Don't wait, start investing now! #FinancialSecurity

V) Updating each user's "news" list in the API with the new message generated.

<img width="732" alt="Screenshot 2023-10-03 at 5 22 47 PM" src="https://github.com/renatamch/BankCustomers/assets/136348810/3c94cb86-7d80-44a9-a91b-c094603f4206">
