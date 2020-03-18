### Reason for the project / use
The project was born out of the need of some acquaintances who use YouTube, this because YouTube changed the policies to keep your ownership of Verified on your channel.
Among the requirements to maintain it, they requested a list of all the channels that could be confused with yours, either because they contain the same words.

### Project description
The project developed at UiPath, is a software robot that performs the following activities:
- Ask the name (with spaces) of the youtube channel you want to search for.
- Extract the list of all channels that contain the words used in the name of the main channel.
- Save in an Excel the list of Channels and their URL's that were found.

### Reminders and Notices.
- By default, the code was configured to run with Internet Explorer, if you want to change your browser, you must go to the Properties of the "Open Browser" activity within the "Main.xaml" file and modify the value of BrowseType.
- Within "Main.xaml" in the "Variables" section, there is a variable called "excelPath", remember to configure the path where you want the excel that the system will generate to be saved. Note: must contain "\" at the End of the path.

### Software Requeriments
In order to run this project, a UiPath Robot and Studio are required.
The project was developed in UiPath Studio Community, which you can download from [UiPath Platform](http://platform.uipath.com/)
