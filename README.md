# MATLAB-IPN-Course
October 27, 2021:
1) Clone the github repository locally
2) If needed, make changes in the folder
3) Now commit the change
4) Push the change- this will add it to the online folder

Using basic commands on windows on cmd prmpt:
cd: go to the current directory
"file.ext" to open the file (open file name.ext in unix)
dir: "lit files under a particular folders (ls in unix)
git add . : adds all the files in that folder to be committed
git add *.txt : adds all the txt files from the folder to be committed
git commit -m "comment"- this adds the name to the changes you just made i.e. commit name "-m" is to add message




October 26, 2021:
Cmd prmpt 
cd.. go one folder up

MATLAB:
pwd         %print working directory/ see where you are in
cd           %change directory

cd ../ 
cd..       % moves you to the directory above 
exist ' '  %to check what the name you added between ' ' is? Output is a number. Each number means something and 
            you have to check that in the MATLAB help feature. Eg: if you type in exist 'xyz'
            the output is 2 that means, it is a .m file.
           % you can find if the input you add is a variable. eg: exist 'x' and output is 1, that means
             x is a variable you have defined in your current workspace. 

close all                                           % clears your workspace environemnt 
clear all                                            % closes all figures
clc                                                     %clears command window


Data types:
1)Boolean variable= Variable with true or false value
logical operators:
Is equal to == (single = is defiing variable value; but if you want to ask the computer (logical operator), it should be ==)
Is greater than >
Is less than <
Is NOT equal to ~= (= operator always on the right of other operators. eg, >= , <=)
The OR operator ||
The AND operator &&

Outputs are 1 or 0


Statement to logical statement:
If its raining or is less than 55, wear a raincoat.
T=(55:100);     % define T
raining=0;      % define raining. Anything othern than 0 while defining a variable is taken as 1 or true. 
                   In which case you wil get an output array of 1 
T<55|raining     % ask if T<55 or raining (which you set as 0), output will be an array of all 0 1x46


2)char — single or array of alpha-numeric symbols ‘ ‘    % they are taken as individual entries in an array
Eg:X = ['ABC' 'CDE']

X =    'ABCCDE

X = ['ABC'; 'CDE']

X =  2×3 char array

    'ABC'
    'CDE'

X = ['ABC'; 'CDE'; 'D']
Dimensions of arrays being concatenated are not consistent.
 
3)string — array of text “ ”
X = ["ABC"; "CDE"; "D"]

X =   3×1 string array

    "ABC"
    "CDE"
    "D"



October 27, 2021  
USEFUL RESOURCE:
MATLAB Special charecters documentation
MATLAB Technical documentation 

We use round brackets for indexing. Or to CALL an element.       %Indexing into a matrix is a means of selecting a 
                                                                  subset of elements from the matrix. 

movefile      %to move files and folders from source to desitnation (see documentation). You can rename files with this.
mkdir         % make new folder, subfolders
load          % load files

use these 2 together:
imread('filename')    %Read image from graphics file
imagesc('filename')   %display the image
image ('filename')


Questions to ask on October 28 session:

1) when would you caturally use pwd? if we just use the command "cd" it gives the same output