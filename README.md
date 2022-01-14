# SF
Skillfctory


# Login   [Login confluence ](https://delfood.atlassian.net/wiki/spaces/DELFOOD/pages/65751/Login)
####### Created by Zakir Mammadov
 

## **Primary path:**

1. User selects sign in
2. User selects sign in with qusername and password
3. User enter username and password
4. System checks Username and Password in Database and if it’s correct
5. System creates token for user
6. User enters into the system

---

## **Alternative path:**

2. a User select OTP login
..* User enter his mobile number
..* System checks checks mobile number in system  and if it’s correct
..* System send SMS with otp to mobile of the user
..* User enter OTP
..* System checks OTP with sended one and if it’s correct
..* System creates token for user
..* User enters into the system

***

Example table 
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


Exception path 1:  

3.aUser enters username and password 

System checks Username and Password in Database and if it’s not correct

System show Error mesage Username and Password isn’t correct

Exception path 2:  

2.a.2User select OTP login

System checks checks mobile number in system  and if it’s not correct

System show Error This mobile number isn’t registered

Exception path 3:  

5.System checks OTP with sended one and if it’s not correct

System show Error You have entered wrong OTP
