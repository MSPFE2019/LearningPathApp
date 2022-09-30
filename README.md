# LearningPathApp


[Downloading Solution Here](https://github.com/MSPFE2019/LearningPathApp/blob/a756060e28b5f3822ae4503c6a895394ffc074ca/LearningPath_1_0_0_3.zip)


## How to Import the solution

*Sign into Power Apps and select Solutions from the left navigation.

*On the command bar, select Import.

*Import solution.

*On the Import a solution page, select Browse to locate the compressed (.zip or .cab) file that contains the solution you want to import.

*Select Next.

*If your solution contains connection references, you’ll be prompted to select the connections you want. If a connection does not already exist, create a new one. Select Next.

*If your solution contains environment variables, you will be prompted to enter values. You will not see this screen if value(s) are already present in your solution or the target environment.

## How create the required SharePoint List

*Navigate to the solution

*Click on "Create_LearningPath_Lists", this will open the flow.

*In the top nav bar, click on "play" button. Their will be series of prompts and then it will ask for the url for the SPO site(pre-existing) that will houses the lists.

*This will take 5 mins to run, check the sites for 3 lists and 1 document library.

*Edit the Learning Path Training app and remove the connections for the SPO site only.

*Re-add the connection by Search for the SharePoint and providing the url to the site. You need to select all the Learning Path artifacts.

*Repeat for the Learning Path Author App

