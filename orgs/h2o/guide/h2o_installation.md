# H2O Installation #

H2O run on Linux, Windows and OSX environment and can be set to run either single node or in clustered mode i.e. running on multiple machine.

### Single Node (Standalone Mode): ###
 - You just need to download h2o binaries and run as Java process. 
 - It is a 2 step process
   - Download the zip and unzip
   - Run it using Java runtime
     - Windows     : C:\h2o_unzip_folder> java -jar h2o.jar
     - Linux & OSX : $ java -jar h2o.jar
 
### Multiple Node (Cluster Mode) : ###
 - You can run multinode H2O in 2 different ways
   - Multicast Method
     - Make sure your network support multicast network
     - Copy h2o.jar on all the machines where you want to run H2O
     - Run H2O jar by passing "-name" parameter with same name on all the machines as below:
       - Machine 1: java -jar h2o.jar -name "my_h2o_cluster_x"
       - Machine 2: java -jar h2o.jar -name "my_h2o_cluster_x"
       - Machine n: java -jar h2o.jar -name "my_h2o_cluster_x"       
     - When all the process with run on all the machines they will find each other and form a H2O cluster
   - Flatfile Method
     - First Copy h2o.jar in all the machines where you want to run H2O
     - Next create a text file (i.e. flatfile.txt) with all the machines IP address where you want to run H2O
     - Copy that text file (i.e. flatfile.txt) to all the machine where h2o.jar is placed
     - Run the command as below on all the machines
       - Machine 1: java -jar h2o.jar -flatfile flatfile.txt
       - Machine 2: java -jar h2o.jar -flatfile flatfile.txt
       - Machine n: java -jar h2o.jar -flatfile flatfile.txt              
 - On Hadoop Cluster as Hadoop MapReduce Job
   - Download Hadoop distribution of H2O as h2odriver.jar
 - On Spark cluster as Spark Job managed by YARN
   - Sparkling Water supports Spark 2.0, 2.1 and 2.2 along with older Spark 1.6  
   - Download Sparkling Water binaries baed on your Spark version as 
 
## Downloading H2O ##


## Installing H2O 

### On Premise ###
 

### Cluster  ###

### Hadoop  ###

### Spark ###

