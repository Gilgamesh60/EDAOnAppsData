# EDAOnGoogleApps

##Intro to project##:
This Project uses data from the apps on the Google Play Store to predict the overall rating a particular app will get from its users. There are a variety of features which will be used by the mode


##Data Collection using selenium##

For getting the data from the Google Play Store this project uses a Selenium based Web Scraper Python script. The script first gets the search results for each letter of the English Alphabet and stores the URLs for each app in a list. After this it iterates through all the unique URLs and grabs the data related to every app.

The data columns which it grabs for each app are : Name, Genre, Last Update, Age Requirement, Android Version Requirement, Number of installations, Current Version, Size, Interactive elements, Company Owned by, The Name of the Developer, Number of Reviews and the Overall Rating of the app.

##Data Cleaning##

Many of the columns in the data which has been scraped is not in the ideal form for performing some Exploratory Data Analysis. For example, the In-app Purchases feature has textual data like '$5 - $25 per item'. This form of data cannot be understood by a machine and we need to get it to a format where it will understand what is going on. For this purpose, Data Cleaning is done. 


##EDA##
I have mentioned the insights gathered from the data in the above EDA notebook.

Following is the distribution of the Genre of Apps in the 0-2, 2-3, 3-4 and 4-5 rating intervals:


![#0-2]("C:\Users\user\Downloads\R2_Genre.png")

![#2-3]("C:\Users\user\Downloads\R3 _Genre.png")

![#3-4]("C:\Users\user\Downloads\R4_Genre.png")

![#4-5]("C:\Users\user\Downloads\R5_Genre.png")

