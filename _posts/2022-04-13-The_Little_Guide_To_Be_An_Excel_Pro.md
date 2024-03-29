---
layout: post
title: The Little Guide to be an Excel Pro!
---
## Five tips to help you use Excel more effectively

Hello, and thank you for coming to my little piece of the internet. I hope that you enjoy your stay😊. Today, I am going to give you five quick tips that will help you advance in your excel usage without coding! You won't have to touch any VBA for this one, nor will you need to program with another language and install some fancy driver to automate stuff - although we will probably get to that in another post one day. If you have read my BIO or my about page, you know that I was a validation engineer. Basically we tested our product to make sure that it satisfies the customer use cases. To do that, we put all of our tests in a database for automated execution as well as progress tracking. In doing this, we used Excel to both manipulate and investigate tests and to generate reports - and I got a lot of questions about using Excel. Today, I am going to answer some of the most common questions as well as provide helpful solutions to what I think are very common issues. 

### 1. Reducing column width.

This is a very common problem that I'm going to describe right now. I'm sure that you have run into this issue one time or another if you use Excel. You have a column that has a lot of text and you want the column to expand so you can see the text instead of viewing your text in the formula bar. You can see in the picture above that cell E2 has a lot more data than fits in the current cell size. To resize the column to auto-fit the amount of data in the cells, you just double click the rightmost edge of the column header when your cursor looks like the cursor in the image below. Then your column should look something like the image below. Now this is great - until you want to size it back down. How do you do that? Well if your column doesn't take up the whole screen, you can grab the same handle that you clicked to resize and drag it to the size that you want. If your column takes up the whole screen, you cannot grab that handle. You then need to manually format the column. To do this, you can select the column by clicking the letter at the top of the column, then you can click the home ribbon tab, then click the down arrow next to format and select column width. Then just type whatever width you want the column to be.

### 2. Pasting across filtered cells

This one can get you into some trouble if you don't follow this little trick. You see in excel, if you have 10 rows of data that you paste into 10 filtered rows The data will be put into the hidden rows that you have filtered out and you could be overwriting data that you don't intend to be writing over. To paste properly, you copy your data by either using <CTRL+C> or right-clicking and selecting copy then you select the range of cells that you want to paste into. Don't paste yet! Select the Home menu in your menu ribbon, look in the Editing section for 'Find & Select' and in that sub-menu click on go to special. In the window of options that pops up. select the radio button next to Visible cells only then you may paste your data. This insures that you don't paste into hidden or filtered cells.

### 3. Mass inserting data from text

This is another really handy trick that a lot of people are not aware of. For these last couple of tricks, I'm going to download a dataset from data.gov. Feel free to download something and follow along. So in the following image, you will see that I have a single column with a bunch of text that is filled with multiple values delimited by commas. In order to split up all of those values into their own columns, you just select the column that you want to split up, open the data menu in your ribbon bar and select the text to columns option in the data tools section. In the window that pops up, tell Excel that your data is delimited or fixed width, let Excel know the character(s) that are delimiting your data, and then hit next and then finish. Now your data is separated nicely into columns. You will see the process and the results in the following four images.

### 4. Removing repeated entries

Sometimes you only want distinct values in a column; maybe you are using that column as a key. Excel can easily remove duplicates in a column and remove the associated rows completely so that you can keep only the first instance of each key. In the data below, you will see that the number of test takers is repeated several times. It's not like one school can't have 10 students because another school already has 10 🤣. So lets just get the first record for each number of test takers. Open up the data menu in your ribbon toolbar and click remove duplicates in the data tools section. In the window that pops up, select the column(s) that contain your duplicate values. In this case, I'm going to just select the Number of Test Takers column. _Et Voila!_ Just like that, the duplicates are removed from our data! You can see the procedure in the following images.

### 5. Sorting by multiple columns

This one is probably the most straightforward one on the list, but I have to look it up every time I need to do something like this because I forget that Excel makes this so simple. Lets say, given our previous data before removing duplicates, that I want to sort by the number of test takers from low to high and then sort the school names alphabetically. It is as simple as selecting your data and then clicking on sort in the sort & filter section of the data ribbon. Then you just add your columns in the order that you want to sort. The reason that I always miss this is because I usually have filtering enabled across my columns and then I just sort the column by hitting the little drop down arrow in the column heading as you will see in the image below. You can deduce the process that I described here from that same image as well.

I hope that you found these 5 quick tips helpful and if you didn't already know about them, I hope that you go on to be more productive when you have to work in Excel. If you like my writing and you would like to see more content in the future, please like, share, and subscribe. You wouldn't want to miss any awesome articles would you?

Until next time, 

Kevin McFarland
