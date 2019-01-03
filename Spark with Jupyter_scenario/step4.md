In this step we would be creating some more files that are required for Spark Application Image.
We already have reference files, we can just copy them to appropriate location.

## Task 1:

Copy the configure jupyter file.<br>
`cp ~/test/configure_jupyter.sh ~/Spark/image/centos`{{execute}}

Copy the configure java file.<br>
`cp ~/test/configure_java8.sh ~/Spark/image/centos`{{execute}}

## Task 2:

We need to add additional configuration fils under appconfig directory, We already have a reference configuration files, To add them follow the below steps<br>

Remove the appconfig folder from the Spark folder<br>
`rm -rf appconfig`{{execute}}

<br>`yum install wget -y`{{execute}}

Add the appconfig reference file using the below command<br>
`wget https://www.dropbox.com/s/9xb2804a1u0fsi5/appconfig.zip`{{execute}}

<br>`yum install unzip -y`{{execute}}

Unzip the file<br>
`unzip appconfig.zip`{{execute}}

Check files under appconfig directory<br>
`ls appconfig`{{execute}}

Remove the unwanted files from the folder<br>
`rm -rf appconfig.zip __MACOSX`{{execute}}

## Task 3:

Copy the Logo file.
<br>
`cp ~/test/Logo_Spark.png ~/Spark`{{execute}}
