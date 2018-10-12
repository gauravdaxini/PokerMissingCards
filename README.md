## Poker Missing Cards
This program is written in Java using the Map Reduce approach which will identify the missing cards from an input deck provided in a text file and print it in the output directory when run through Hadoop.

### Pre-Requisite
- [Java installed](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-get-on-ubuntu-16-04) on the machine.
- [Hadoop installed](https://www.digitalocean.com/community/tutorials/how-to-install-hadoop-in-stand-alone-mode-on-ubuntu-16-04) on the machine.
- [Eclipse](http://www.eclipse.org/downloads/packages/release/2018-09/r/eclipse-ide-java-ee-developers) installed on the machine.

### Build Dependencies
Add the following libraries in the projects build path.
- [Hadoop Core](https://mvnrepository.com/artifact/org.apache.hadoop/hadoop-core)
- [Apache Commons CLI](https://mvnrepository.com/artifact/commons-cli/commons-cli)

### Create Project Archive
Export the java project as a Jar File.

### Run
````
hadoop jar PokerMissingCards.jar com.bigdata.hadoop.mapreduce.PokerMissingCards PokerInputCards.txt OutputDir
````
