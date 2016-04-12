## Demo notebooks for Apache Zeppelin
##### Update your Zeppelin instance with all notebooks in this repo:
  - If you are using hortonworks sandbox, you can execute command below to get latest notebooks: </br>
  `curl -sSL https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/update_all_notebooks.sh | sudo -u zeppelin -E sh`
  - Please note that if you have changed or created your own notebooks they will be moved to a folder: /opt/incubator-zeppelin/notebook/old_yyyyMMdd-HHmmss, you can copy them back to /opt/incubator-zeppelin/notebook/ directory

##### Importing specific notebooks:
Copy the "JSON" link URL from the table below and paste it into Zeppelin's import from URL tool.
![Import UI](/screenshots/import.png?raw=true)

##### Demos:

| Description	| Components | Code	| View	| Author | Comments	|
| ------------- | ----- | ---------- 	| ------------  | --------  | --------  |
| Starter Bank demo | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/raw/master/2A94M5J1Z/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQTk0TTVKMVovbm90ZS5qc29u/) | NFLabs | Default notebook installed by Zeppelin |
| Australian Spending dataset | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANTDG878/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQU5UREc4Nzgvbm90ZS5qc29u/) | [Ned Shawa](https://twitter.com/nedshawa) |  |
| Australian Spending dataset | Hive | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANT56EHN/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQU5UNTZFSE4vbm90ZS5qc29u/) | [Ned Shawa](https://twitter.com/nedshawa) |  |
| Map Earthquake dataset | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2ANTDG878/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQVBGVE4zTlkvbm90ZS5qc29u/) | NFLabs | |
| IoT Trucking demo | Spark/SparkSQL | [json](https://github.com/hortonworks-gallery/zeppelin-notebooks/blob/master/2AS5TY6AQ/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQVM1VFk2QVEvbm90ZS5qc29u/) | [Nauman Fakhar](https://github.com/nfakhar), [Dhruv Kumar](https://github.com/DhruvKumar) | Demo from Hadoop Summit |
| Intra-day stock prices | Phoenix | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B21B3AYC/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjIxQjNBWUMvbm90ZS5qc29u/) | [Ali Bajwa](https://github.com/abajwa-hw) |  |
| Magellan: Geospatial Analytics Using Spark | Spark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B4TWGC8M/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjRUV0dDOE0vbm90ZS5qc29u) | [Ram Sriharsha](https://github.com/harsha2010) | [Magellan Blog](http://hortonworks.com/blog/magellan-geospatial-analytics-in-spark/) as Zeppelin Notebook. *Requires Spark 1.4.1* See [here](https://github.com/harsha2010/magellan) for more details |
| Twitter sentiment analysis using Spark Streaming | Spark streaming | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B522V3X8/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjUyMlYzWDgvbm90ZS5qc29u) | [Guilherme Braccialli](https://github.com/gbraccialli) | |
| PySpark tutorial: Analyzing network intrusion dataset with Python and Spark  | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2B48PF7SN/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQjQ4UEY3U04vbm90ZS5qc29u) | [Saptak Sen](https://github.com/saptak) | |
| Single view demo | Hive/Sqoop/HDF | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BBBW75VS/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkJCVzc1VlMvbm90ZS5qc29u)  | [Ali Bajwa](https://github.com/abajwa-hw)/Ajay Singh | Notebook version of [Single view lab](https://github.com/abajwa-hw/single-view-demo) |
| Predicting Airline Delays | Spark/MLLib | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BB5CUPUW/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkI1Q1VQVVcvbm90ZS5qc29u) | [Ofer Mendelevitch](https://github.com/ofermend) | Related to this [Blog post](http://hortonworks.com/blog/data-science-apacheh-hadoop-predicting-airline-delays/) and [part 2](http://hortonworks.com/blog/data-science-hadoop-spark-scala-part-2/) |
| Sensors Predictive Analysis | SparkSQL/PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BAVUZ7NA/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkFWVVo3TkEvbm90ZS5qc29u) | [Vedant Jain](https://github.com/vedantja) | Adding Predictions to this [Blog post](http://hortonworks.com/use-cases/sensor-data-hadoop-example/)
| Hands-on Tour of Apache Spark in 5 min | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BEQE47HR/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2hvcnRvbndvcmtzLWdhbGxlcnkvemVwcGVsaW4tbm90ZWJvb2tzL21hc3Rlci8yQkVRRTQ3SFIvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) |  
| Lab 101: Intro to Spark with Python | PySpark | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BFGYS3YT/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3NhZ2Fya3Vsa2FybmkzNTkyL3plcHBlbGluLW5vdGVib29rcy9jb3JyZWN0XzJCRTNLRDRHNi8yQkUzS0Q0RzYvbm90ZS5qc29u) | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Intro to Spark Core & Spark SQL with Word Count
| Lab 102: Intro to Spark with Scala | Spark SQL | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BJVW65WS/note.json) | view | [Robert Hryniewicz](https://github.com/roberthryniewicz) | Intro to Spark SQL using Airlines Dataset
| HDFS Space Usage Visualization | HDFS / D3.js | [json](https://raw.githubusercontent.com/hortonworks-gallery/zeppelin-notebooks/master/2BFAUAD4F/note.json) | [view](https://www.zeppelinhub.com/viewer/notebooks/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2dicmFjY2lhbGxpL0hkZnNVdGlscy9tYXN0ZXIvemVwcGVsaW4vbm90ZS5qc29u) | [Guilherme Braccialli](https://github.com/gbraccialli) | A D3.js Sunburst visualization to explore HDFS space utilization and other metadata info, [more details](https://github.com/gbraccialli/HdfsUtils/)

