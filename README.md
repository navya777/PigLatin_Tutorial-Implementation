# PigLatin_Tutorial-Implementation
Airline Analysis using Amazon AWS and piglatin
1)Create a folder Assignment1 in namenode and created Input and Wordcount_classes folder  to respectively place input and class files used Cyberduck.

2)Copy WordCount.Java to Assignment1 and used following command to create Classes.

   Change directory to folder where java file is located using :
   Cd /home/ubuntu/WordCount.Java
   Execute:
  /usr/local/hadoop/bin/hadoop com.sun.tools.javac.Main -d WordCount_Classes  WordCount2.java
  
3)Classes created can be seen under wordcount_classes ,now we have to create jar file .

    from Class using command
     jar cf WordCount2.jar wordcount_classes/*.class
    Jar file called wordCount2.jar will be created in Assignment1
 4)To execute jar file provide input and output folder
/usr/local/hadoop/bin/hadoop jar WordCount2.jar WordCount2 /Assignment1/Input /Assignment1/output





AMI Names:
Linux_NavyaMartinKollapally
DataNode1_NavyaMartinKollapally
Datanode2_NavyaMartinKollapally
Datanode3_NavyaMartinKollapally

