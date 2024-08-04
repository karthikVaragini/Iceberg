### Setup Spark with Iceberg and Hive Spark version 3.4.0

### 1. Download and Configure Iceberg with Spark.. Iceberg Version 1.4.2
1. Download Iceberg Spark Runtime JAR: version 1.4.2
    ```sh
    wget https://repo1.maven.org/maven2/org/apache/iceberg/iceberg-spark-runtime-3.4_2.12/1.4.2/iceberg-spark-runtime-3.4_2.12-1.4.2.jar
    ```
2. Add the JAR to Spark:
    ```sh
    spark-shell --jars /path/to/iceberg-spark-runtime-3.4_2.12-1.4.2.jar
    ```

### 2. Install Hive and Start Thrift Server
1. Download and Install Hive
2. Ensure Thrift Server is running and provide that in the configuration.




