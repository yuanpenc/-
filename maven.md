### IDEA使用Maven出现jar包无法导入的万能解决方案
mvn install:install-file 
 -DgroupId=com.oracle 
 -DartifactId=ojdbc14
 -Dversion=10.2.0.4.0 
 -Dpackaging=jar 
 -Dfile=D:\ojdbc14.jar
