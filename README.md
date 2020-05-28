# easy-copy-with-random-name-java
<html><h3>A Simple Java Method to Generate a Copy of a Certain File with a Random File Name</h3><html> 

This Can be Used in a Situation Like Where You Want to Store A Copy of A File That is in Your Computer in to Your Project Folder
And at the Same Time Give That File an Uniqe Random Name

I Created This to Get A User Selected File Using JFileChooser And Store A Copy Of That File in My Application Installation Directory 
So Even If User Deleted The Original File It Will Not Be A Problem For My Application Since It Has A Copy of That File Already Stored.

<html><h4>This Method Also Returns The File Path Of The Newly Copied File As A String.</h4></html>

Just copy and paste the method into your java class file where you need to use this functionality 
and call the method by inputting following parameters.

source_path --> Path of The Source File as a String 

You Can Use Absolute Path Of the file or Path in Your Project If you Have That file Already Imported into Project Folder Previously
(Depends on Your Need)

Absoulute Path Eg: "C:\Users\UserName\Pictures\flower.png"
Project Path Eg: "src\\images\\flower.png"

destination_path --> Path of The Destination File as a String

randomprefix--> a simple String you like as the prefix of random destination file name

Eg: If You input lest Say "img" to this yoy file name will look like  "img1564646541.<extention_you_gave>"

extention --> Extention of The Output File

<html><h3>Note</h3><html>

Remember to Give Your Extention Starting With a Dot(".")

Eg: ".png"

Happy Coding :-)
