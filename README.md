# Financial Calculator in the Property Analysis Application 

The finacial calculator calculates certain fields and autpopulates them within the CRM

## Solution Creation
1. We first created a form that looks up the property from the property analysis form using a function
Please refer to this code (https://github.com/Evergreen-Investments/Financial-Calculations/blob/main/Auto_Populate_Fields)

![image](https://user-images.githubusercontent.com/124835926/222195816-f9397fda-bfc4-4b0b-9f8d-459a2c957f58.png)
![image](https://user-images.githubusercontent.com/124835926/222196642-df889df6-a136-4c76-aad3-9e69114bb7c6.png)

2. Within that function it also calculates the fields and autpopulates the calculation fields

![image](https://user-images.githubusercontent.com/124835926/222196785-d35077ec-8b2b-4b3f-a755-c32bdf51f16a.png)
![image](https://user-images.githubusercontent.com/124835926/217661572-f643a7c4-f320-4b5b-8dac-94f7d6562d54.png)

3.After it's submitted we created a function that updates the CRM
Please refer to this code (https://github.com/Evergreen-Investments/Financial-Calculations/blob/main/Calc_Update_CRM)
![image](https://user-images.githubusercontent.com/124835926/222197183-fcf1ea71-d544-4b29-90c3-b4d4cf2fb653.png)

4.Then in order to populate the property database module in the CRM we created a function that moves all values
from the formula fields to single line fields
Please refer to this code (https://github.com/Evergreen-Investments/Financial-Calculations/blob/main/Formula_to_Single_Line.txt)
![image](https://user-images.githubusercontent.com/124835926/222198968-c580a22b-1941-4410-ad23-c462cbbf4b11.png)

5. Then we do the same process, and move the single line to currency and decimal fields
Please refer to this code (https://github.com/Evergreen-Investments/Financial-Calculations/blob/main/Single_Line_to_Currency)

## Diagrams
![image](https://user-images.githubusercontent.com/124835926/222197348-4e4345c7-dee7-4b3c-8778-b48abf006c9a.png)
![image](https://user-images.githubusercontent.com/124835926/222197466-5d7634f1-e18c-45d5-8521-38966a9513e3.png)
