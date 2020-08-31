# SENSED
one-Shot lEaNning geSture rEcognition Dataset

# Overal Description
All the files follow the same structure and contain 9 values in each row. The first field denotes the Epoch time in milliseconds that the data arrived in the application, the second field includes the relative timestamp, as reported by the OS, where the data arrived, the next six fields include the x, y, and z axis values of the accelerometer and the gyroscope sensors respectively, while and the last field contains the label for the executed gesture. The label takes values from 0 to 45, where 0 denotes the character "A", 25 the character "Z", 26 the character "0", 35 the character "9" and 36 to 45 the special characters in the order that are described above. 

# Dataset Contents/Subjects
|Set | Characters | No. Subjects | No. Subjects |
| :---: | :---: | :---: | :---: |
| training | A-Z | 25 | 26 |
| validation | 0-9 | 5 | 10 |
| test | $#€?!%*+= | 5 | 10 |
| total|  | 35 | 46 |
