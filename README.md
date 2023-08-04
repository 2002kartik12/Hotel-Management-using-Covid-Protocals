# Hotel-Management-using-Covid-Protocals
This project was made in the C++ programming language.
Here the user gets the rooms according to their choice but they must have to give RT-PCR report. If it is positive then automatically they will allot a Covid Patient Rooms.
Admin can delete, modify the details of customer at any time.
User can also delete, modify the details and get the bill information from their room.
There is the Restaurant, games and according to that the amount will add to their bill.
Concept used is Data handling, array, string, switch, if-else.


![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/a027fb33-85c2-4618-adb5-031e3783ef3a)
WE CHOOSE CHOICE 1i.e.ADMIN LOGIN 
Fig2. Login Screen
Login screen for admin and for customers here admin have the highest priority since only admin can add, delete, search, update customer as well as hotel records.  On the other hand, availability of rooms can be checked by the customer through customer login.

 ![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/cda5a312-c083-4fd9-9863-99245f3aa7e2)
 Fig3. Invalid Login Details screen
If admin enters wrong details only 1 more chance will be left otherwise the system will revert back to the login page.

 ![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/7464d5e7-a418-48f2-920c-c652bde954a9)
Fig4.Admin:-
    Admin Login ID: 1
   Password: 2
Login page for the admin. The system can be accessed when the correct login details are entered. Only admin can edit records of hotel and customers.
 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/f7616133-fa7c-41ed-b745-3e41b5a9b800)
Fig5. Main Menu Screen
        Options to handle records
After the login details are entered the main menu will open providing various options to the admin through which he can access, add, search, view and delete the various records in the system. 


WE CHOOSE CHOICE 1 i.e. BOOK A ROOM 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/2be8afb0-6667-49a4-b7b4-2dbd25118c55)
Fig6. Add Customer
        Here first admin asked for covid report if customer don’t have report then extra charge will be applied and then admin asked that he/she is corona positive or negative.
Accordingly, the room will be allocated to customer.
If  you enter the choice as 1. The booking screen will open through which customer can book his room by giving his personal information. If the customer is identified as covid positive he will be automatically allocated quarantine room according to the government norms. Since it is now being mandatory to bring a RT-PCR report so as to enter hotel if a customer fails to provide the report certain hotels are provided with testing kits where his reports can be provided to identify whether he is covid positive or negative. Hotel will take a certain charge for the test.
 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/fd7dbad6-51b6-487c-bb74-b8bce6d2d17e)
Fig7. Add Room screen (Invalid room number entered)
        Here customer is Corona positive and he entered room no. 2 which is available for only non-covid customers.   A message will be shown that “Sorry, Room does not exist. You must select rooms from room no.101 to 150.” The same instance will happen if non covid customer tries to book a room from 101 to 150 since rooms 101 to 150 are allotted only for covid patients.

WE CHOOSE CHOICE 2 i.e. CUSTOMER RECORD 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/ede907d6-c585-418b-8076-319652d875f5)
	Fig8. Customer Record
To Search and display the details of customer
Through main menu the admin can enter through customer details and can search for a specific room to check whether the room is booked and can also check the record of that customer.


WE CHOOSE CHOICE 3 i.e. Room Allocated 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/386a9eb2-ac00-4c46-a955-4e61aae51517)
Fig9. Rooms Allocated
Here we can see all rooms which are already allocated
Through Main menu screen the admin can go to the customer rooms allotted screen where he can check the records for all the rooms that have been allotted in the hotel.

WE CHOOSE CHOICE 4 i.e. Memo 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/a12beb85-c3f4-427a-87ba-33314ae85e15)
	Fig10. Memo Screen
Here customer can book a memo/program.
Through main menu the admin can enter the memo screen through which he can book various programs for the customers according to their choice.

 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/4bbabbe0-3c1b-460f-9e66-8a4e8d533761)
	Fig11. Memo Screen
If a customer staying in room no. 55 wants to book swimming pool along with two others (staying in his room) he will be charged per person and the total charge will be added to his checkout bill.

 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/5f3940c0-dfd8-470f-b086-6d9d8c7a6b2b)
	Fig12. Memo Screen
Here again room No.55 customer book a program 1(Theatre).
The previous amount (Rs.600) and current amount (Rs.1500) both will be added to the bill.


 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/85852a2e-8330-4d06-b181-b59c91e5a0e0)
Fig13. Memo Screen
If a room which is vacant is entered.

 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/50b06235-82c5-4601-9119-9fac1da58961)
Fig14. Casino Carnival
If the user wants to play the casino he will be asked to enter his money deposit.
 

![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/52d41d0a-e040-4fd0-99f1-7a3ce09ddee4)
	Fig15. Casino Screen
After the customer adds his balance he will be asked to put a bet and the number on which he wants to put his bet. If the customer has lost, he will be asked if he want to play the casino again.	


![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/87047fd1-7b49-4c25-8295-462f5f3e3838)
Fig16. casino Screen

WE CHOOSE CHOICE 5 i.e. EDIT 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/2edd41f7-7563-4c01-b394-bfeb9d33bd18)
Fig17. Edit Menu Screen
Through Edit records from main menu the customer records can be edited.


 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/41f67f14-7738-42cf-becb-34e043f4672e)
	Fig18. Modify Menu Screen
       If the customer wants to modify his records his records.


 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/40ff68ab-bce9-4667-b682-b8276e498ac3)
Fig19. Modify Phone Number Screen
          The customer records for room no. 55 are modified.

WE CHOOSE CHOICE 6 i.e. ORDER FOOD  
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/7cd2b65b-340a-4364-add5-9c96773e16a9)
Fig20. Restaurant menu screen
Customer from room no. 55 ordered lunch for three people.
This amount will be added to the Bill.


 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/55ca5a65-b548-472e-a23e-f443abce56dd)
Fig21. Restaurant Menu Screen
Here again room No.55 customer book Order Food type 3(Dinner)
The previous amount (Rs.3000) and current amount (Rs.1200) both will be added to the bill.


WE CHOOSE CHOICE 7 i.e. GENERATE BILL 
  ![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/4d31feba-d2ae-48d4-a783-37117012b076)
Fig22. Billing Screen
On the billing screen, customers total bill will be shown along with taxes and GST charged by the hotel.
The customer will be asked if he want to check out.


 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/e4284d71-e98c-4451-b572-6d30259ac172)
	Fig23. billing Screen
If the customer refuses to check out he will be asked to add the number of days that will be added to his stay.
He will be charged accordingly.

 IF AGAIN WE CHOOSE CHOICE 7 i.e. GENERATE BILL 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/611ec222-ec5a-4d1b-b7af-8d133bcff65c)
	Fig24. Billing Screen
    Then admin ask to enter payment method.
If a customer wants to checkout he will be allowed to pay his cash through different payment methods and                   discount will be provided accordingly.
 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/8dbd0225-1410-45f1-8da0-6b284197468c)
	Fig25. Invoice
Here the customer wants to pay his bill through credit card he will be provided discount and his final bill will be shown.






AFTER EXITING FROM ADMIN LOGIN USER SELECT CHOICE 2 i.e. CUSTOMER LOGIN 
![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/4e2ab16d-8aad-454f-80e0-9ec1a587d81b)
	Fig26. LOGIN Screen
If user enters through customer login. The user will be asked the room for which he wants to see the records.

  ![image](https://github.com/2002kartik12/Hotel-Management-using-Covid-Protocals/assets/110666936/9ac3eed8-cdfb-44bb-b499-9810cdf7b378)
 Fig27. Customer Portal
The Details of existing customer will be displayed.

