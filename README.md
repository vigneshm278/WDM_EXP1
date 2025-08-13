### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 13/08/2025
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------

@relation employee

@attribute name string
@attribute id  numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
Ganesh,101,high,2,male,7810048370
Sangavi,102,low,3,female,9812309871
Tamizhselvan,103,medium,1,male,9884787511
Jeevitha,104,low,5,female,7418985619
Sarwesh,105,high,6,male,8987213092

--------------
Weather Data
---------------
@relation Weather

@attribute outlook {sunny,overcast,rainy}
@attribute temperature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}

@data
sunny,85,85,true,no
overcast,80,85,false,yes
rainy,70,75,false,no
rainy,75,70,true,no
rainy,64,80,false,yes
overcast,60,65,false,yes
sunny,85,85,true,no
overcast,79,85,false,no
overcast,80,90,false,yes
rainy,70,75,false,no
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:

<img width="1227" height="728" alt="Screenshot 2025-08-07 154222" src="https://github.com/user-attachments/assets/3fddcbd4-7b1a-408d-bd48-3782e6460c32" />

<img width="746" height="448" alt="Screenshot 2025-08-13 131923" src="https://github.com/user-attachments/assets/4d23f8e6-9567-4b70-988c-d0e91945dbe4" />





### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
## Employee Table after adding new attribute place:
<img width="1228" height="731" alt="Screenshot 2025-08-07 154832" src="https://github.com/user-attachments/assets/1dc9bf92-01b4-47d1-9460-c33db73545e8" />


## Weather Table after adding new attribute Place:


<img width="743" height="449" alt="Screenshot 2025-08-13 132102" src="https://github.com/user-attachments/assets/a346ffa4-62e4-4c65-9095-ce122b55f966" />



### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

##  Employee Table after removing attribute phone:

<img width="1231" height="727" alt="Screenshot 2025-08-07 155642" src="https://github.com/user-attachments/assets/34fc0f0c-1436-4925-8074-a195d6df4c49" />

## Weather Table after removing attributes Humidity:

<img width="744" height="441" alt="Screenshot 2025-08-13 133300" src="https://github.com/user-attachments/assets/05401928-c37a-41b7-bfa1-46d7e45b6b78" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:

##  Employee Table after Normalizing id and exp:
<img width="1228" height="730" alt="Screenshot 2025-08-13 132733" src="https://github.com/user-attachments/assets/02435b80-a208-48c6-bda3-bdc1c7b400f4" />


##  Weather Table after Normalizing temperature and humidity:
<img width="1229" height="734" alt="Screenshot 2025-08-13 132756" src="https://github.com/user-attachments/assets/55205bdc-b548-4dcc-adb4-d9f920990540" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.

 
