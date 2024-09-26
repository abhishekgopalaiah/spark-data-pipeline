spark-submit --conf "spark.driver.extraJavaOptions=-Dlog4j.configuration=log4j.properties" --py-files data\lib.zip  HelloSpark.py .\data\sample.csv


spark-submit --conf "spark.driver.extraJavaOptions=-Dlog4j.configuration=log4j.properties" HelloSpark.py .\data\sample.csv                    