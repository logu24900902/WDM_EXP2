### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buys_computer

@attribute age {<=20,20-40,>40}
@attribute income {low,medium,high}
@attribute student {yes,no}
@attribute credit_rating {fair,excellent}
@attribute buys_computer {yes,no}

@data
<=20,high,no,fair,no
20-40,low,yes,fair,yes
>40,medium,yes,fair,yes
<=20,low,no,fair,no
>40,high,no,excellent,yes
<=20,low,yes,fair,yes
20-40,high,yes,excellent,no
>40,low,no,fair,yes
<=20,high,yes,excellent,yes
>40,high,no,fair,yes
<=20,low,yes,excellent,no
>40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
<=20,medium,yes,fair,yes
>40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
<img width="1232" height="730" alt="image" src="https://github.com/user-attachments/assets/80e483ee-40cf-4517-a079-c1c93d0a548e" />




### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dfe29d30-1167-46d7-b1fb-08dfe5e2c317" />



### RESULT: 
thus the code was errorless and runed successfully
