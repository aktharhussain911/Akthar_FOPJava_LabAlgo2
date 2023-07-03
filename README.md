# Akthar_FOPJava_LabAlgo2

I have uploaded two Java Projects:

<b>1 - CurrencyNoteCount

2 - TransactionTarget

1 -  CurrencyNoteCount</b>

<b>CurrencyNoteCount</b> is the solution to the following problem : 

<b>Problem </b>


PayMoney. processes thousands of transactions daily amounting to crores of Rupees.
They also have a daily target that they must achieve.
Given a list of transactions done by PayMoney and a daily target, your task is to determine at which transaction PayMoney achieves the same.
If the target is not achievable, then display the target is not achieved.

<b>TestCase 1 </b>

enter the size of transaction array

enter the size of transaction array

3

enter the values of array

20 12 31

enter the total no of targets that needs to be achieved

2

enter the value of target

21

Target achieved after 2 transactions 

enter the value of target

19

Target achieved after 1 transactions 

<b>Explanation</b>

Target 1 i.e 21 is achieved after 2 transactions, (20 + 12)

Target 2 i.e 19 is achieved in the 1st transaction itself.


<b>-------------------------------------------------------</b>

<b>Test Case 2</b>

enter the size of transaction array

1
enter the values of array

100

enter the total no of targets that needs to be achieved

1

enter the value of target

101

Given target is not achieved 

<b>Explanation →</b> Since there is only 1 transaction that is of 100 and the target value is 101, hence target is not achieved.


<br>
<br>
<br>
<b>2 -  TransactionTarget</b>
<br>
<br>

<b>TransactionTarget</b> is the solution to the following problem : 

<b>Problem </b>

You are a traveler and traveling to a country where the currency denominations are unknown
and as you travel you get to know about the denomination in random order.

You want to make a payment of amount x, in such a way that the higher denomination is used to make exact payment.


<b>Input</b>

Take input of all the currency denominations ( random order)

Take input of the amount that you want to pay.

<b>Output</b>

Print the minimum no of notes that you will be using to pay the net amount.


TestCase 1

enter the size of currency denominations 

3

enter the currency denominations value

5

1

10

enter the amount you want to pay

12

Your payment approach in order to give min no of notes will be

10:1

1:2


<b>TestCase 2</b>

enter the size of currency denominations 

5
enter the currency denominations value

60

5

12

78

25

enter the amount you want to pay

128

Your payment approach in order to give min no of notes will be

78:1

25:2


<b>TestCase 3</b>

enter the size of currency denominations 

4

enter the currency denominations value

12

5

123

18

enter the amount you want to pay

158

Your payment approach in order to give min no of notes will be

123:1

18:1

12:1

5:1

