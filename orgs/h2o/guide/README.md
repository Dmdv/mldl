# H2O - User Guide #

 - The code snippets will be in R, python, scala and java

### [1. Architecture](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_arch.md) ###
 - What is it?
 - How it works?
 - What Algorithms are supported with H2O?
 - What you can do with H2O? 
 
### [2. Installation](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_installation.md) ###
 - On Premise
 - [Cluster](https://github.com/Avkash/mldl/blob/master/orgs/h2o/h2o_installation.md)
 - Hadoop
 - Spark
 
## [3. Accessing H2O library](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_access.md) ##
   - Web Frontend (FLOW)
   - Python
   - R
   - Scala

## [4. Starting H2O cluster](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_start.md) ##
   - FLOW
   - Python
   - R
   - Scala
   
## 4. [Data Ingest](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_data_ingest.md) ##
 - [Supported File Formats](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_data_ingest.md#supportedfileformat)
 - [Supported Data Types](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_data_ingest.md#supporteddatatypes)
 - [Supported Data Source](https://github.com/Avkash/mldl/blob/master/orgs/h2o/guide/h2o_data_ingest.md#supporteddatasources)
 - Ingesting data in H2O
   - Importing a File (FLOW | Python | R | Scala)
   - Importing Multiple Files (FLOW | Python | R | Scala)
   - Uploading a File (FLOW | Python | R | Scala)
 - Ingesting data from SQL (Python | R)
 - Understanding Data distribution in memory
  
## 5. Data Manipultion ##
 - Splitting Datasets into Training/Testing/Validating  (Python | R | Scala)
 - H2O Pandas Dataframe and vice-versa (Python)
 - Merging Two H2O Dataframes (Python | R | Scala)
 - Group By operation on data frame (Python | R | Scala)
 - Combining Columns from Two Data Frames (Python | R | Scala)
 - Combining Rows from Two Data frames (Python | R | Scala)
 - Slicing Rows from an H2O data frame (Python | R | Scala)
 - Slicing Columns from an H2O data frame (Python | R | Scala)
 - Fill NAs in H2O data frame (Python | R | Scala)
 - Replacing Values in a H2O data frame (Python | R | Scala)
 - Imputing values into H2O Data frame (Python | R | Scala)
 - Pivoting data frames (Python | R | Scala)
 - [Slicing the data](https://github.com/Avkash/mldl/blob/master/orgs/h2o/h2o_data_man.md)

## 6. Machine Learning Algotithms with Code ##
  - Supervised 
    - GLM
      - Classification Example (FLOW | Python | R | Scala)
      - Regression Example (FLOW | Python | R | Scala)
    - GBM 
      - Binomial Classification Example (FLOW | Python | R | Scala)
      - Regression Example (FLOW | Python | R | Scala)
    - Distributed Random Forest
      - Multinomial Classification Example (FLOW | Python | R | Scala)
      - Regression Example (FLOW | Python | R | Scala)
    - Deep Learning
      - Classification Example (FLOW | Python | R | Scala)
      - Regression Example (FLOW | Python | R | Scala)
    - Naïve Bayes Classifier
    - Stacked Ensembles
  - Unsupervised 
    - KMeans (FLOW | Python | R | Scala)
    - PCA (FLOW | Python | R | Scala)
    - GLRM (FLOW | Python | R | Scala)
  - Miscellaneous 
    - Word2Vec (Python | R )
    
## 7. Sparkling Water ##
 - Installation
 - Launching Cluster (deploy mode - client vs cluster)
 - Machine Learning in Sparkling Water
 - pysparkling
   - GBM Example
   - DRF Sample
 - rsparkling
   - GBM Example
   - DRF Sample

## 8. pysparkling ##
 - Installation
 - Connection spark cluster
 - Machine learning example (GBM | GLM)
 
## 9. rsparkling ##
 - Installation
 - Connection spark cluster
 - Analyzing Job and data
 - Machine learning example (GBM | GLM | Deep Learning)
 
## 10. H2O on Hadoop Cluster ##
 - Launching Cluster 
 - using various parameters ( ip | port | disown)

## 11. H2O Models in Production ##
 - Supported Scenarios
 - Exporting Models
   - Binary  (FLOW | Python | R | Scala)
   - POJO and MOJO models (FLOW | Python | R | Scala)
 - Scoring Model
   - in-cluster scoring (FLOW | Python | R )
   - POJO Scoring
     - Classification Sample in Java | Scala
     - Regression Sample in Java | Scala
   - MOJO Scoring
     - Classification Sample in Java | Scala
     - Regression Sample in Java | Scala
   - Hive Scoring
     - Hive UDF Sample in Java

## 12. H2O Performance ##
  - Cluster size approximation
  - Analyzing data in H2O memory

## 13. Advance Concepts ##
  - Grid Search
    - Classification Example (FLOW | Python | R | Scala)
    - Regression Example (FLOW | Python | R | Scala)
  - Hpyerparameters 
    - Classification Example (FLOW | Python | R | Scala)
    - Regression Example (FLOW | Python | R | Scala)
  - AutoML
    - Classification Example (FLOW | Python | R | Scala)
    - Regression Example (FLOW | Python | R | Scala)
  - Cross-Validation
  
## 14: Important Links ##
 - [H2O Website](https://www.h2o.ai/)
 - [Latest Download Page](https://www.h2o.ai/download/)
 - [Documentation](http://docs.h2o.ai/h2o/latest-stable/index.html)
 - H2O Open Source Projects at Github
   - [H2O-3](https://github.com/h2oai/h2o-3)
   - [Sparkling Water](https://github.com/h2oai/sparkling-water)
   - [H2O4GPU](https://github.com/h2oai/h2o4gpu)
   - [H2O Meetups](https://github.com/h2oai/h2o-meetups)
   - [H2O Tutotrials](https://github.com/h2oai/h2o-tutorials)
 - [H2O Bugs and Open Issues]
   - [H2O JIRA Dashboard](https://0xdata.atlassian.net/secure/Dashboard.jspa)
   - [H2O-3 JIRA](https://0xdata.atlassian.net/projects/PUBDEV/issues)
   - [Sparkling Water JIRA](https://0xdata.atlassian.net/projects/SW/issues)   
 - [H2O StackOverflow Tags](https://stackoverflow.com/questions/tagged/h2o)
 - [H2OStream Community Mailing List](h2ostream@googlegroups.com)
 - H2O Enterprise Support
   - [Support Website](https://support.h2o.ai)
   - [Support Email](support@h2o.ai)
 
