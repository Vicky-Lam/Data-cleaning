# Data-cleaning

Hey there! Thank you for your interest in this repo. I am working on a project that analyses people's conversations. I am presenting the codes I wrote here hoping to encourage other social scientists like me to use Python and its libraries to clean up their data saved in an excel (even though it's textual!). 


Here are some key points that I would like to demonstrate in this repo:
    1. We often have data that can easily take up 10,000+ lines and many columns. pandas.DataFrame.drop will help you drop columns irrelevant to your research. 
    2. A lot of textual data must be coded manually, but sometimes it will be very tedious to repeatedly fill the cells with the same code. pandas.DataFrame.fillna can help you fill the empty cells using the value above. 
    3. You can also remove some rows that contain certain values in a specified column by using pandas.Series.str.contains. 
    4. After you have done your cleaning, don't forget to save your data in a more organized way using pandas.ExcelWriter.


##About my data here:
![sample](https://user-images.githubusercontent.com/75769044/105940825-16931c00-6097-11eb-9660-95f20657222d.PNG)

Hope you enjoy my repo!
