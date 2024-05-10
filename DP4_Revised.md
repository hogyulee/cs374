Prototype Iteration
=============================
## Link to our prototype
https://www.figma.com/file/ia4SioSHfC1FXcNjWnatXV/Paymily?type=design&node-id=1%3A1186&mode=design&t=n5l06nbPqKkPaFnK-1

## Representative screenshots
![image1](https://github.com/hogyulee/cs374/assets/66636839/61852dc3-d63a-409a-bca8-82252b030727)
![image2](https://github.com/hogyulee/cs374/assets/66636839/29a11f96-30b0-4638-9a77-1c1c94dfe5ab)
![image3](https://github.com/hogyulee/cs374/assets/66636839/ce40f458-d401-402a-8187-ea6f984254ca)
![image4](https://github.com/hogyulee/cs374/assets/66636839/189310a7-1b23-455c-a132-af740aebfd58)

## How we improved Digital Prototype from DP3. & How we revised the Tasks/Scenarios from DP3.

## Before 5/9(Fri)

In the last DP3, we received feedback that our prototype needed to include features for parents and children to communicate. In our service, children spend within a preset budget discussed with their parents, but the ability to set or adjust that budget was not included in our prototype or task.

We added a chat function in preparation for DP4. This work was done immediately after DP3 was completed so it is also detailed in DP3's Studio Reflections. To explain briefly again, children and parents can communicate freely through chat like in other chat apps. And if your child presses the "Request more budget" button on the Categories Tab, they will automatically be taken to the message screen and can request more budget. We wanted to check this newly added feature in DP4, so we added "Request Increase on Budget for Book Category" as Task 5 to check whether this feature works well for users.

There were also minor modifications. 
- We increased the size of text and buttons that were too small to be seen. 
- We also had flow issues. After making a payment in an external app, the screen had to return to the original external app, but there was a flow that did not match the reality, such as the screen returning to the main screen of our app. This flow was modified to meet the user's expectations. 
- In task3 and task4, the feature of switching receiver did not work well, but this has been fixed to work properly.
- Due to our mistake in the last DP3, Task 2 did not support end-to-end scenario. There was no available action in category page. We corrected this mistake and modified the flow so that the end-to-end scenario of Task 2 can be performed correctly.


## After 5/9(Fri)

Unfortunately, we were unable to reflect all of DP3's feedback before 5/9. So, after 5/9 DP4, we additionally reflected some of the feedback from DP3. 

- We decided to combine the existing Task 1 and Task 2. This is because Task 2 is not directly related to our POV, but is a form of a subtask of Task 1 into one task. 

- The feedback of payment approval from the parents was missing in task 3 and task 4. Feedback on payment approval has been added as a notification. After approval is made, the user can be notified that permission has been granted through the notification icon on the top bar. When the user clicks the icon, the user can also check the contents of the permission. An action to check the notification was added to Task 3 and Task 4. The final revised Tasks(Task 1 and Task 2 combined, Action added to Task 3 and Task 4) are at the bottom of the report.

Heuristic Evaluation Request Form
=============================

## HE Requester Information 
Team name: HCI Wizards

Team members’ names: Gyuho Lee, Jiwoong Jang, Sejun Jung, Youngseo Cho

You are a minor who has no personal income or account and relies on your parents for spending. You use the Paymily app to request payment from your parents. Paymily is an app that allows you to spend within a preset budget for each item category. For spending outside the budget, payment can be made by sending a separate payment request to the parents.

## Digital Prototype Test URL(s): 
https://www.figma.com/file/ia4SioSHfC1FXcNjWnatXV/Paymily?type=design&node-id=1%3A1186&mode=design&t=n5l06nbPqKkPaFnK-1

## Goals
Our team wants to receive feedback about the following aspects of the service.
 - make it easy for miners to send requests to their parents upon request.


## Persona 

### User: June
 
### Persona - User scenarios

June is 16 years old high school student. He lives in Seoul and he lives with busy working parents, sibling, and grandmother. He has no personal income and depends on his parents' allowance. He often uses his parents' cards for online gaming, shopping, and food delivery.


### Persona - Goals

He wants a simpler and faster way to get permission from his parents.

### Persona - Tasks

Complete Food Delivery Payment(Within Budget)
Check Remaining Balance
Send Request for Permission and Payment for Clothes(Exceeds Budget)
Add Another Family Member to Permission Request
Request Increase on Budget for Book Category



  


## POV &  Tasks 

### POV
Minors who rely on parental funding for online purchases need a faster and simple way to get payment permission. A streamlined, real-time method would allow minors to make purchases easily while maintaining necessary parental oversight.

### Task #1: Complete Food Delivery Payment
![image11](https://github.com/hogyulee/cs374/assets/66636839/d2468ab4-494d-4d76-9096-f04d1c40569c)

### Task #2: Check Remaining Balance
![image22](https://github.com/hogyulee/cs374/assets/66636839/c38d07f5-cf52-4fd6-b739-4bb95a136b49)

### Task #3: Send Request for Permission and Payment for Clothes
![image33](https://github.com/hogyulee/cs374/assets/66636839/70507fbb-8448-4b38-80e9-b28900c3e794)

### Task #4: Add Another Family Member to Permission Request
![image44](https://github.com/hogyulee/cs374/assets/66636839/7db2733c-ebf9-48bc-8bf5-72d889ec7e5b)

### Task #5 : Request Increase on Budget for Book Category
![image55](https://github.com/hogyulee/cs374/assets/66636839/8e14e4dd-23ed-4f0b-87e3-0eb57900c571)


## Background and technologies 

![tech](https://github.com/hogyulee/cs374/assets/66636839/5c1a72c2-994b-40b3-9cd0-c43eb031c8cc)

Card information is not stored on minors’ devices.
The payment request for the item the minor wishes to purchase is sent directly to the parent and payment is made on the parent's device. Until then, payment completion will not be processed in the external app on the minor’s device.
If the request is made within the budget, it is automatically approved; if it is outside the budget, the request is approved after the parent firsthand accepts it.


Adding and editing family members is done by the representative.



## Implemented Tasks via Digital Prototypes 

The tasks here are based on 5/9 DP4. Our tasks modified after 5/9 are attached after these.

## Task #1: Complete Food Delivery Payment
![image1](https://github.com/hogyulee/cs374/assets/66636839/61852dc3-d63a-409a-bca8-82252b030727)

1. Start from the Food Delivery screen.(Flow3)
2. Click Anywhere. 
3. Review the recipient[수취인] and price.
4. Check consent details[약관 동의 내용].
5. Try to refuse the agreement and see what happens.
6. Proceed  to complete the payment process.
7. Confirm successful payment completion.

## Task #2: Check Remaining Balance
![image2](https://github.com/hogyulee/cs374/assets/66636839/29a11f96-30b0-4638-9a77-1c1c94dfe5ab)

1. Review the remaining balance available for food purchases.  
2. Navigate to the Categories
- a. Click the [more] button on the categories section on the main page
- b. Or Click Categories in bottom bar
- c. Or Click Food category (move to instruction 3)
3. Move to Food Category
4. Observe the remaining balance displayed.
5. Verify accuracy and understand the available budget for food purchases.


## Task #3: Send Request for Permission and Payment for Clothes
![image3](https://github.com/hogyulee/cs374/assets/66636839/ce40f458-d401-402a-8187-ea6f984254ca)

1. Start from external shopping app screen (Flow 2)
2. Unlike Task 1 , immediate payment is not possible. Find out why it's impossible.
3. Try to select someone other than Brad as the target of the payment request.
4. Send a payment request to the selected family member.
5. Go back to the home page.



## Task #4: Add Another Family Member to Permission Request
![image4](https://github.com/hogyulee/cs374/assets/66636839/189310a7-1b23-455c-a132-af740aebfd58)

1. Move to processing request
- a. Click processing request on main page
- b. Or Click the [more] button on Requests section and click processing request.
2. Add an additional family member for approval
- a. Click the [change] button and choose any person you want
- b. Click the [request] button
3. Verify the update request status
4. Go back to the home page.

## Task #5 : Request Increase on Budget for Book Category
![task4](https://github.com/hogyulee/cs374/assets/66636839/2d2749e8-934e-469b-ba43-10c9dd9c41a9)

1. Send request message for increasing budget to “Mary”
- a. Navigate to “Categories” page
- b. Choose “Book” category
- c. Request more budgets to Mary. 
2. Check requesting chat
> Now you have sent a request to Mary, and automatically moved to the chatting page. Further chatting to get permission is given.
- a. Read the chat
- b. Press “send message..”
- c. When the keyboard pops up, press the send button.

## Revised Tasks (After 5/9)

These are the tasks we have modified after DP4(5/9).

## Task #1: Complete Food Delivery Payment and Check the Remaining Balance

![image1](https://github.com/hogyulee/cs374/assets/66636839/61852dc3-d63a-409a-bca8-82252b030727)
![image2](https://github.com/hogyulee/cs374/assets/66636839/29a11f96-30b0-4638-9a77-1c1c94dfe5ab)

1. Start from the Food Delivery screen.(Flow3)
2. Click Anywhere. 
3. Review the recipient[수취인] and price.
4. Check consent details[약관 동의 내용].
5. Try to refuse the agreement and see what happens.
6. Proceed  to complete the payment process.
7. Confirm successful payment completion.
8. Review the remaining balance available for food purchases.  
9. Navigate to the Categories
- a. Click the [more] button on the categories section on the main page
- b. Or Click Categories in bottom bar
- c. Or Click Food category (move to instruction 3)
10. Move to Food Category
11. Observe the remaining balance displayed.
12. Verify accuracy and understand the available budget for food purchases.


## Task #2: Send Request for Permission and Payment for Clothes
![image3](https://github.com/hogyulee/cs374/assets/66636839/ce40f458-d401-402a-8187-ea6f984254ca)

1. Start from external shopping app screen (Flow 2)
2. Unlike Task 1 , immediate payment is not possible. Find out why it's impossible.
3. Try to select someone other than Brad as the target of the payment request.
4. Send a payment request to the selected family member.
5. Go back to the home page.
- a. Check if new notification have arrived to you.
- b. Go to notification page.
6. Check whether your request was processed correctly.

## Task #3: Add Another Family Member to Permission Request
![image4](https://github.com/hogyulee/cs374/assets/66636839/189310a7-1b23-455c-a132-af740aebfd58)

1. Move to processing request
- a. Click processing request on main page
- b. Or Click the [more] button on Requests section and click processing request.
2. Add an additional family member for approval
- a. Click the [change] button and choose any person you want
- b. Click the [request] button
3. Verify the update request status
4. Go back to the home page.
5. Go to notification page
6. Check whether your request has been approved

## Task #4 : Request Increase on Budget for Book Category
![task4](https://github.com/hogyulee/cs374/assets/66636839/2d2749e8-934e-469b-ba43-10c9dd9c41a9)
![dp4_2](https://github.com/hogyulee/cs374/assets/66636839/ed132699-9f7b-4c6c-b0c2-fde293b2ae49)
1. Send request message for increasing budget to “Mary”
- a. Navigate to “Categories” page
- b. Choose “Book” category
- c. Request more budgets to Mary. 
2. Check requesting chat
> Now you have sent a request to Mary, and automatically moved to the chatting page. Further chatting to get permission is given.
- a. Read the chat
- b. Press “send message..”
- c. When the keyboard pops up, press the send button.
