# customer_banking
This customer banking system allows a user to input their savings balance and cd balance, interest rates and the number of months the user will be earning interest for each account, which in turn calculates the user's updated balances with interest, as well as the interest earned in that time. </br>

The `customer_banking.py` file is where the program starts by asking the user input for their balances, interest rates, and amount of time they will be earning interest in months. This file uses the logic imported from `savings_account.py` to calculate the updated savings balance and interest earned on that account. `customer_banking.py` also uses logic imported from `cd_account.py` to calculate the updated cd balance and interest earned on that account. </br>

Both `savings_account.py` and `customer_banking.py` import the `Account` class from `Account.py` in order to create `Account` instances and apply the logic accordingly to set the balance and interest. </br>

The `customer_banking.py` returns the updated savings balance and interest earned, as well as the updated CD account balance and interest earned on that account to the user. </br>

<b>Sources</b> </br>
Slack from Brandon (thank you) regarding the print input and output for the user `customer_banking.py` `lines 13-15, 25-27, and 33-34` - https://aipteastoctob-ypv8330.slack.com/archives/C07K473EQCF/p1730495819736569 </br>

03-Python-Programming-2/3/Activities/05-Ins-Creating_Modules </br>
03-Python-Programming-2/3/Activities/06-Stu_Bank_Account_Class </br>
Both of these exercises for logic in `savings_account.py` and `cd_account.py` </br>
https://stackoverflow.com/questions/9752958/how-can-i-return-two-values-from-a-function-in-python - Understanding returning two values in `savings_account.py line 35`, `cd_account.py line 34` and `customer_banking.py lines 17 and 18`
