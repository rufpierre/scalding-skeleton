Ce projet est un example d'utilisation de scalding avec un "Fat Jar". Il est repris et adapté du tutorial "Cascading for the Impatient", partie 8, exemple 3 (https://github.com/Cascading/Impatient/tree/master/part8). Il destiné à être utilisé comme un squelette d'application scalding en mode "Fat Jar".

This project is a simple scalding exemple using a "Jat Jar". The code is the reproduction/adaption of the exemple3 of part 8 of the tutorial "Cascading for the Impatient" (https://github.com/Cascading/Impatient/tree/master/part8). It's intented to be used as a skeloeton to build a "Fat Jar" scalding application.

Use:

    mvn clean package

    rm -rf output
    hadoop jar target/part8-1.0.0.jar Example3 --hdfs --doc data/rain.txt --wc output/wc
    
    rm -rf output
    hadoop jar target/part8-1.0.0.jar Example4 --hdfs --doc data/rain.txt --stop data/en.stop --wc output/wc
