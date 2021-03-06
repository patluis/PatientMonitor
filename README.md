# PatientMonitor
App for monitoring patients (both in hospitals and at home)

## Phase 0: Branching Strategy
I was researching different branch strategies for GitHub and came across one called the Git Flow Branch Strategy. I have decided to loosly follow this strategy. I have several branches that will all be used for different purposes. 
The main branch will be used for any deployable code I have completed.
The developing branch will be used for any sections of the app that are mostly finished. 
Features branch will be used for specific features within the app as I develop them. 
Finally, the needs-fixing branch will be used for any parts of the app that I am working on that are only in the beginning stages and need a lot of work before complete. 
I have decided to use this method to organize my code because it can properly keep track of all of the stages of my code as I develop them. As I progress from needs-fixing to the developing I will merge completed code into the main branch and that will be what is ready for deployment. 

## Phase 1: Device Module
### Json Schema
1. Patient Name: Name of Patient 
2. Date: Date of Service
3. Device: Choose a device 
4. Data: Enter the data correlated with said device 
5. Unit: Choose a unit that correlates with the device


### Chat Schema 
1. Incoming User ID
2. Outgoing User ID
3. Time Sent 
4. Date Sent

### Device Module 
Webpage that allows users to fill in patient information. Uses both write in and drop down menu.


<img width="407" alt="Screen Shot 2022-05-13 at 8 22 30 PM" src="https://user-images.githubusercontent.com/60165420/168403884-21e1cda9-de78-436f-a3c4-69a0f72d50b0.png">


## Phase 2: Cloud Hosting
Use Flask as a Web Service Platform, and deploy it onto AWS.

