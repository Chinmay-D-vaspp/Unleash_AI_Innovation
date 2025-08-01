# Exercise 3 – Integration of SAP Document AI and Process Automation into Build Apps

1.  Select Integration Tab and click on “ADD INTEGRATION”.
    ![](./Exercise%203.img/ex3.img01.jpg)

2.  Under SAP Systems select BTP Destinations.
    ![](./Exercise%203.img/ex3.img02.jpg)

3.  We can see the list of Destinations that are set in our BTP Cockpit. Select the destination set for SAP Doc AI, in our case it is Docx_Destination and then click on Save.
    ![](./Exercise%203.img/image_ex3.png)
    
5.  Select Install Integration.
    ![](./Exercise%203.img/ex3.img04.png)
    
7.  Click on Add Rest API Data Entity, to post the data from Build Apps to Documentation AI.
     ![](./Exercise%203.img/ex3.img05.jpg)
    
9.  The Dialog is popped up. Fill the details as below:
    *   **Name**: GET
    *   Select the checkbox for **Autogenerate Configuration**
    *   **Entity path within the api**: `/document/jobs`
    *   Select the checkbox for **Retrieve Only**
    *   Click on **Add**
    ![](./Exercise%203.img/image_ex3_2.png)

10.  Click on **Run Test** and you should get status 200.
    ![](./Exercise%203.img/ex3.img07.jpg)
