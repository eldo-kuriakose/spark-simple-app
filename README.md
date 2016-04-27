# spark-simple-app

## To run as a standalone spark app

#### create jar file
sbt package
##### Run in spark

spark-submit --class "SimpleApp" --master local[4] target/scala-2.10/simple-project_2.10-1.0.jar
