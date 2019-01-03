In this step we would be creating some more files that are required for Spark Application Image.
We already have reference files, we can just copy them to appropriate location.

## Task 1:

Copy the configure jupyter file.<br>
`cp ~/test/configure_jupyter.sh ~/Spark/image/centos`{{execute}}

Copy the configure java file.<br>
`cp ~/test/configure_java8.sh ~/Spark/image/centos`{{execute}}

We need to add additional configuration fils under appconfig directory, We already have a reference configuration files, To add them follow the below steps<br>

Remove the appconfig folder from the Spark folder<br>
`rm -rf appconfig`{{execute}}

Add the appconfig reference file using the below command<br>
`wget https://www.dropbox.com/sh/l6hz6gm4ts6v4bp/AABav35WtpjYeIp3MVE4DxLpadl=0`{{execute}}

Check files under appconfig directory
`ls appconfig`{{execute}}

Copy the Logo file.
<br>
`cp ~/test/Logo_Spark.png ~/Spark`{{execute}}
