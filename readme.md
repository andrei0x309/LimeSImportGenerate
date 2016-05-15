#LimeSurveyImportGenerate

Here is a small php class script that can help you generate an output for LimeSurvey import process. It works with an array of lines on the following form:

###Example of array:
```
$arr = [
'\#1#Question Group 1 text',
'\#2#Question 1 text',
'\#3#Answer 1',
'\#3#Answer 2',
'\#3#Answer 3',
'\#2#Question 2 text',
'\#3#Answer 1',
'\#3#Answer 2',
'\#1#Question Group 2 text',
'.',
'.',
'.',
'.',
'\#2#Question n text',
'\#3#Answer 1 of question n',
'\#3#Answer n of question n',
];
```
You can get to this form of array with regex and a text editor that supports regex, i do that all the time. 
Make sure you do the needed changes to the class if you want to use other types of questions as this script was used for radio choice questions.