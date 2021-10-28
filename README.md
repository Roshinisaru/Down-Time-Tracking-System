# Down-Time-Tracking-System
###### INSTRUCTIONS

1.	Go to SharePoint homepage & click on the settings icon on the top right hand side of the page

2.	Select ‘Site Contents’
![image](https://user-images.githubusercontent.com/93128777/139223040-8593346a-d0c7-4252-afef-cf65825bc6e1.png)

3.	Select list under the ‘New’ drop down. Name the list as downtime_system.
![image](https://user-images.githubusercontent.com/93128777/139223997-643a39bd-659b-4d06-b58e-5a09f6a56316.png)

4.	Click ‘Add column’ and add these columns: 
  - Product_Name – single line of text
  - Status – single line of text
  - Date_Time – Date and time
            *(make sure the columns are named exactly as shown above, as it has to match what we have in the power apps system.)
![image](https://user-images.githubusercontent.com/93128777/139224109-f5b4f1d5-4ef7-4013-a233-57537f65055a.png)

5.	There is a title column created when the list is created and make sure it’s marked as not required field under list settings. This is what the list should finally look like.
![image](https://user-images.githubusercontent.com/93128777/139224458-b6cbbd5d-e23c-486b-b0e5-c1ba2b01b8e0.png)

6.	Download the power app from Github. 
- Upload the app to power apps by following the on-screen instructions
![image](https://user-images.githubusercontent.com/93128777/139224690-b9c56b66-a69d-4706-ab5f-7e426b401313.png)
![image](https://user-images.githubusercontent.com/93128777/139224700-dbd8b33c-e254-418c-889d-2b8fea64b059.png)

7.	After the successful upload, open the app in edit mode. Then apply these settings: 

- Upon entering into the system, click the data option from the left side menu. 
- Click the Add data menu and then search for SharePoint in the search box right above it
- Select the SharePoint that appears & choose your SharePoint site link
![image](https://user-images.githubusercontent.com/93128777/139224858-2b48a89a-6b3b-4ee2-86dd-ad60ba436ab2.png)

- Select the downtime_system list to connect the previously made list to the power app. Now you have successfully connected the SharePoint list to the Down Time Tracking System.

Main Screen of the App:
![image](https://user-images.githubusercontent.com/93128777/139225582-122b44f0-e5ae-496c-b628-c573d52902fe.png)

Select ‘Enter System Status’ to register new information
Enter System Status Screen:
![image](https://user-images.githubusercontent.com/93128777/139225645-2746ff49-9f4c-4c5c-a843-4b286f05b0c5.png)

Enter the Product name, Status, and Date & Time (it’s set default to today’s date). Hit the save button beside the row. The app will automatically add an empty row below so that you can enter multiple product’s system status, and finally hit save button at the bottom of the page to insert all the information into the SharePoint list. *Note – please note that you have to hit the save icon beside each row in order to save to the backend.
![image](https://user-images.githubusercontent.com/93128777/139225692-7fb7a103-11d9-40d4-b93e-354cbba0ebd7.png)

Now going back to the main screen, there’s another button named Update/view System  Status
![image](https://user-images.githubusercontent.com/93128777/139225748-ee3dd192-783b-4fad-a4f8-68f216b2cab1.png)

Upon selecting that, it takes us to a screen where we can view our previously entered   products and their information. When selecting a product, you will be able to view and update a product’s information. 
![image](https://user-images.githubusercontent.com/93128777/139225839-4d6396d1-3bc8-4319-80a3-cc5cb8dfda5c.png)
Finally, hit the save button at the bottom right of the page to update the product information.





