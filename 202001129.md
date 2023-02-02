# Lab-1_202001129

Name: Deep Jaimesh Shah


Identifying Functional and Non-Functional Requirements

### Q.1. Identify FRs and NFRs of LIS.

#### Functional Requirements:

* The librarian must have complete control of the system and all the authorities.<br>
* Only the librarian can have the access to enter an new record or delete an existing one.<br>
* The library staff must have access to all the transactions.<br>
* Issuing and returning books can be done by the members of the LIS only.<br>
* Non-members can still browse the books online although they cannot issue any book.<br>
* There has to be a portal wherein the non-members can buy the membership if they are eligible.<br>
* Users can extend the deadline to return a particular book, if there is no one waiting/demanding for that book.<br>
* If a member wants to issue a book already issued by someone else, his request must be queued, and he can issue the book only after the fist user returns it.<br>
* Approriate fine must be charged from the member if he fails to return the book on the due date.<br>


#### Non-Functional Requirements:

* Portability - the system must be portable so that when we have reached the maximum limit, we can incorporate the same system with upgraded hardware or software.<br>
* Security - the data of users, administrator, and librarian must be kept secure so that no one can misuse it. Also the passwords must br encrypted and then stored.<br>
* Maintainability - the system must be such that it takes minimal efforts and resources to maintain.<br>
* Fault tolerant - the sytem must be reliable and must know how to deal with all kinds of user input so that it does not lead to system failure.<br> 
* Scalability - the system must comprehend with the number of users it handles.
* Performance - it is an important metric for evaluation. The performance of the system should not decline in any scenario. Users must not wait for long to process their request.<br>
* Integrity - if a book is issued to someone, it must not be displayed as available in the menu to other users. The system must be updated on each and every operation it performs.<br>
* Flexibility - the system should easily adapt any new changes that the administrator wants to bring in the system.<br>
* User friendliness - the system must be easy to use and it must not require any special training to operate the system. Also various language options should be made available to cater all type of audience. Voice assistant can also be provided.<br>


### Q.2. Identify scope, features and non-functional aspects of the following problem.

#### Scope:

The hearing aid solution aims to assist the community using Artificial Intelligence to detect the surroundings and make the users aware of what is going on. It can be easily linked to the user’s android device for all time access. The updates would be conveyed with the help of signals and screens to notify the user. Moreover the system is built to work in real-time to enhance the user experience. 


#### Functional aspects:

* It can access the microphone of the mobile device to record the surrounding sounds.
* It detects sounds and notifies the user by displaying them on the mobile screen and also vibrates the device.
* The application runs in the background, to capture any sound that might require an immediate alert notification.
* The software uses a pre-trained AI model to identify sounds.
* Users can record and enter custom sounds for some custom notifications if they want.
* Users can choose to prioritize the notifications over other notifications and applications.


#### Non-Functional Aspects

* The application has a simple UI that can be easily understood by the user.
* The application is active all the time in the background for emergency alerts but for normal use it must be opened.
* The software prioritizes the alert notifications over the other notifications on the mobile screen, irrespective of the user using any other application.
* The software notifies the user within few seconds of sound detections (low latency).
* The software could work without any internet connection for day to day sounds.
* The data stored about the sounds should be correct, consistent, and reliable.
* The application is compatible with any android device with 4GB of RAM.
