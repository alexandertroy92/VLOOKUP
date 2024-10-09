# VLOOKUP
# How to use VLOOKUP function in EXCEL

VLOOKUP is one of Excel's most powerful Lokup functions.
If data is organized in vertical columns you can use VLOOKUP function to search the first column(OrderID) of your data table and return a corresponding vlaue from another column(Product).

![image](https://github.com/user-attachments/assets/681bf1a2-cfcc-4c82-a9c3-cbaba107387f)

# Lets take a look at an example of VLOOKUP function in EXCEL.

First, you'll need a table of data containing order information, similar to the one shown above. We can use VLOKUP to locate a product based on a particular Order ID value. To get started lets begin with typing the VLOOKUP command inside EXCEL.

VLOOKUP Command: =VLOOKUP(

![image](https://github.com/user-attachments/assets/f496beff-f03b-47f4-bbc8-ba8ab40baccc)

# VLOOKUP fucntion takes 4 parameters.
1st parameter needs a value that we trying to locate in the first column of the table. In this example we want to search for Order ID 10450.

![image](https://github.com/user-attachments/assets/93c939fb-f5b4-4a36-b01e-09ba04fd8e3e)

2nd parameter we need to enter the source of the data VLOOKUP will use. The range provided must include both the first column that will be searched for our first parameter value and second the column containing our hopeful result. We will need to proivde a range of cells for this parameter. For this example we will enter range A1:B6.

![image](https://github.com/user-attachments/assets/244019b3-f3aa-4b12-bb53-58dddaee5b3c)

3rd parameter we will enter the position number in the table where the return value can be found. Since we are looking for the name of a product we will eneter 2 which represents cells B1:B6

![image](https://github.com/user-attachments/assets/53033de5-d2d3-4d85-a857-98c7577c273b)

4th parameter and most important, this parameter determines weather an exact match or an approximate match will be done when looking for the first parameter. FALSE = exact match. TRUE = approximate match

![image](https://github.com/user-attachments/assets/1280bbac-7159-4ff0-bf18-2f7c45d8eb04)
