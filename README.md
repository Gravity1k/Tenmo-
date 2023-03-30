# Module 2 Capstone - TEnmo

Congratulations—you've landed a job with TEnmo, whose product is an online payment service for transferring "TE bucks" between friends. However, they don't have a product yet. You've been tasked with writing a RESTful API server and command-line application.
## Use cases
1. As a user of the system, I need to be able to register myself with a username and password.
   1. A new registered user starts with an initial balance of 1,000 TE Bucks.
   2. The ability to register has been provided in your starter code.
2. As a user of the system, I need to be able to log in using my registered username and password.
   1. Logging in returns an Authentication Token. I need to include this token with all my subsequent interactions with the system outside of registering and logging in.
   2. The ability to log in has been provided in your starter code.
3. As an authenticated user of the system, I need to be able to see my Account Balance.
4. As an authenticated user of the system, I need to be able to *send* a transfer of a specific amount of TE Bucks to a registered user.
   1. I should be able to choose from a list of users to send TE Bucks to.
   2. I must not be allowed to send money to myself.
   3. A transfer includes the User IDs of the from and to users and the amount of TE Bucks.
   4. The receiver's account balance is increased by the amount of the transfer.
   5. The sender's account balance is decreased by the amount of the transfer.
   6. I can't send more TE Bucks than I have in my account.
   7. I can't send a zero or negative amount.
   8. A Sending Transfer has an initial status of *Approved*.
5. As an authenticated user of the system, I need to be able to see transfers I have sent or received.
6. As an authenticated user of the system, I need to be able to retrieve the details of any transfer based upon the transfer ID.
7. As an authenticated user of the system, I need to be able to see my *Pending* transfers.

![Tenmo1](https://user-images.githubusercontent.com/111000174/228884119-bd3c8ce4-e5bf-44f3-9d2a-3572ef70c1b2.PNG)
![tenmo2](https://user-images.githubusercontent.com/111000174/228884131-fc8deec6-be65-4903-b87a-4c6b08d50ccc.PNG)
![tenmo3](https://user-images.githubusercontent.com/111000174/228884145-fc131634-5bf9-488d-8950-05740297f296.PNG)
![tenmo4](https://user-images.githubusercontent.com/111000174/228884153-ef4e5078-c12d-4947-ab56-9bb21c7b26d1.PNG)
![tenmo5](https://user-images.githubusercontent.com/111000174/228884170-8335a48d-2f2e-44be-83f5-c71a29a0caa8.PNG)
![tenmo6](https://user-images.githubusercontent.com/111000174/228884179-06bffb68-83cc-4935-a202-25b9ea5b2629.PNG)


