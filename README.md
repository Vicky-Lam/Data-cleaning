# Data-cleaning

Hey there! Thank you for your interest in this repo. I am working on a project that analyses people's conversations. I am presenting the codes I wrote here hoping to encourage other social scientists like me to use Python and its libraries to clean up their data saved in an excel (even though it's textual!). Here are some key points that I would like to demonstrate in this repo:
    1. We often have data that can easily take up 10,000+ lines and many columns. pandas.DataFrame.drop will help you drop columns irrelevant to your research. 
    2. A lot of textual data must be coded manually, but sometimes it will be very tedious to repeatedly fill the cells with the same code. pandas.DataFrame.fillna can help you fill the empty cells using the value above. 
    3. You can also remove some rows that contain certain values in a specified column by using pandas.Series.str.contains. 
    4. After you have done your cleaning, don't forget to save your data in a more organized way using pandas.ExcelWriter.



About my data here:
The conversations were audio-recorded and transcribed into an excel file in a format like this:
                                  T:    Did you see that ludicrous display last night? 
                                  S:    Oh, yah! It was crazy.

Then the conversations were coded based on the research purposes. They became something like this:
TV    T    E    Question    25    T:    Did you see that ludicrous display last night?    Talking about a football game
NaN   S    R    Response    26    S:    Oh, yah! It was crazy.                            Talking about a football game

However, the data must be kept confidential at the moment, so I replaced some texts with random letters using pandas.DataFrame.replace:
TV    T    E    N1          25    T:    Rxx xxx xxx xxxx xxxxxxxxx xxxxxxx xxxx xxxxx?    Kyyyyyy yyyyy y yyyyyyyy yyyy
NaN   S    R    H1          26    S:    Tx, xxx! Ex xxx xxxxx.                            Kyyyyyy yyyyy y yyyyyyyy yyyy


Hope you enjoy my repo!
