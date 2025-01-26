## Instructions for WCA workshop

### UserCase 1 : Liberty Modernaisation

--------

Note : Before starting this, Please ensure the necessary installations mentioned in pre-requesites 

#### Step 1: Chat Window

As soon as you click on the WCA icon, if the API key is having required credentials, you should be able to see the chat window. You can explore further with the help of prompt library to get started. 

![Chat Window](./Images/1.chatWindow.png)

#### Step 2: Import Java Project

Import the Java project into VS code

![Import Project](./Images/2.importJavaProject.png)

#### Step 3: Explain Application

Right click on the src folder and go to WCA menue and then click on Explian Applicaion 

![Explain Application](./Images/3.ClickExplainApplication.png)

The expain application will take few minutes to genreate

![Explain Application in progress](./Images/4.ExplainApplicationInProgress.png)

After the expliaination genration is completed, you can see the message as shown below

![Explaination Completed](./Images/5.ExplainApplicationCompleted.png)


To View the explaition click on Show explaination
![View explaition](./Images/6.ViewOutputOfExplain.png)

If you want to save the explaintaion, you can do the same by clicking on the save explaination button. 


#### Step 4: Modernize run time to Liberty

Below are the series of tasks that need to be completed inorder to modernize the application currently running on webshpere to liberty

1. Rightclick on the source and choose the modernize to libery option 

![Modernize to Liberty](./Images/7.ModernizeTolliberty.png)

2. Wca will prompt options for analysing application 

![Analyze applciation](./Images/8.ViewAfterAnalyzingApplication.png)

3. Choose the migration Bundle that is already available in the project 

![Choose Migration Bundle](./Images/9.ChooseMigrationBundle.png)

4. After choosing the migration bundle, we will get option to add the config files for liberty, choose the files to add to current project
![Choose config files](./Images/10.ChooseConfigFilesToAdd.png)

5. After the above step, now we should be able to view the list of issues that are currently present that is preventing project to run on liberty. 
![Current issues](./Images/11.ViewIssuesforLibertyModernaization.png)

6. Before fixing the issue, let us try to run this application and check whehter the logout functionality is working fine and the liberty is configured correctly
![Run liberty](./Images/12.StartLibertyServer.png)

7. Get the pornumber for liberty server
![Liberty address](./Images/13.ObtainTheServerAddress.png)

8. From the help of browser hit the liberty endpoint address
![Liberty on Browser](./Images/14.OpenLibertyEndpointUsingBrowser.png)

9. Click the logout button, you will notice the application breaks.
![Logout](./Images/15.OnClickOfLogout.png)

10. View the reason for applicaition failure

![Logs](./Images/16.ViewException.png)

Now click on the fix auto fixes button, the WCA is able to fix the auto fixes by itself. 

11. After fixing the auto fixes, view the fixes that are mentioned under assisted fix 

![Assited fix](./Images/17.AfterClickingFixAutofixesAndBuild.png)
![Assisted fix](./Images/18.TakeAlookatAssistedFix.png)

12. Choose the entire class from the IDE and click on the help me button

![Assisted fix Help me](./Images/19.ChooseEntireClassAndclickHelpme.png)

13. Copy paste the code from the chat window to the class file and pom.xml file, the changes should look like below

![Changes in pom file](./Images/20.Changes%20inPomfile.png)
![Changes in class file](./Images/21.AfterPastingtheCodeGeneratedByWCA.png)

14. Save the file changes and click on build and refresh
![Build and refresh](./Images/22.BuildAndRefresh.png)

15. Notice that all issues are fixed and now you can verify whether the same is fixed by clicking the logout button in browser
![All issues are fixed](./Images/23.AllIssuesAreFixed.png)
![Verify logout](./Images/24.VerifyWhetherTheLogoutIsworking.png)