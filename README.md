# Claims Management System

This is a full-stack MFPE project built as part of Cognizant ADM JAVA FULL STACK internship.

Following services are part of the application:
## Frontend:
* Member Portal

## Backend:
* Authorization microservice
* Member microservice
* Claim microservice
* Policy microservice

## Requirements
* Java 8
* 

## Setup

Launch the above mentioned 4 microservices in your IDE. Import the project as `Maven Project` and wait for the dependencies to install. If any port is unavailable in your machine you can change the port for the respective microservice in the `application.properties` file under `Backend/microservice/src/main/resources/application.properties`

After the 4 microservices are up and running launch the ClaimApp in the browser.

## Usage

### Initial Launch

On initial launch of application the user is prompted with a home page of the application. In the navigation bar user can click the `Login` button for authentication.
![Login page](https://user-images.githubusercontent.com/55060443/162374330-d05b32f8-2c5d-4741-bba5-eb0fbd071841.png)




### Login Portal

User has to enter his username and password to login. Following credentials can be used to login:

| Username   | Password| 
| -----------|:--------|
| admin     | admin    |
| shraddha  | shraddha |

![loginpage](https://user-images.githubusercontent.com/55060443/162374653-133b403c-3d79-461f-b6dc-faa1d436321c.png)





## Logged In

Authenticated users can now access the features of the application from the navigation bar under their username.

![alt-text](https://github.com/AayushBangroo/ij025Team3ClaimsManagement/blob/master/Usage%20Images/Features.png)




## Claim Portal

Registered users can enter their Member ID to view their bills which include Due Amount, Last paid date and Premium Amount. 
Use Member ID `M101` to view this user's bills.

![claimPage](https://user-images.githubusercontent.com/55060443/162376551-116554fe-9c88-4218-b194-663151355241.png)

## Submitting a Claim

If a user wishes to submit a claim, the submit claim form can be used where the user can enter details regarding Member ID,hospital,policies, etc. Based on the details provided the status of the claim is decided to be either `pending` or `rejected`. User will also be alloted a `Claim ID` for future reference.

![SubmitClaim](https://user-images.githubusercontent.com/55060443/162376546-b434f663-2e48-432c-a6e8-af73ffb29221.png)

## Viewing Claim Status


The user can view the claim status at any time using the `Claim ID` generated in the previous step using the Claim status portal.


![Check StatusPage](https://user-images.githubusercontent.com/55060443/162376831-15855037-4b7b-4fa1-8d14-e592be057d79.png)

## Bill Status


The users can see their bill status in this.

![ViewBillPage](https://user-images.githubusercontent.com/55060443/162376532-ad7b84e5-96d1-489d-8cf2-a082a29737a2.png)




## Developers

* [Shraddha Hemawat]
* [Sukhmeet Singh]
* [Sumiksha Gupta ]
* [Samarth Bhargava]
* [Himanshu Kumar]
