In this step we will extract the contents of the .bin file.
For this execute the following command.<br>
`./bdcatalog-centos7-bluedata-spark221-1.0.bin --payload`{{execute}}
<br>
This will create two files in the directory. (to view the files execute the following command)<br>
`ls`{{execute}}
<br><br>Untar the payload.tar file by executing the following command
<br>`tar xvf payload.tar`{{execute}}
<br><br>This will create new directories. (to view the files execute the following command)<br>
`ls`{{execute}}
<br> Remove the bin file to save space on th device
<br>`rm -rf bdcatalog-centos7-bluedata-spark221-1.0.bin`
<br><br>Navigate to the new directory, and untar the file by executing the following command
<br>`cd bdcatalog-centos7-bluedata-spark221-1.0`{{execute}}
<br>
`tar xvf bdcatalog-centos7-bluedata-spark221-1.0-src.tgz`{{execute}}
<br><br>Now navigate to the directory created after the above step
`cd bdcatalog-centos7-bluedata-spark221-1.0-src`{{execute}}
<br><br>
Copy the content of this directory to the directory you created initially
`cp -R * ~/Source/Spark`{{execute}}
