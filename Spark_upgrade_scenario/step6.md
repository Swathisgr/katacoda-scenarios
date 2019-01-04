In this step we will make changes in our Dockerfile.<br>

We already have a reference Dockerfile. We just need to replace the current Dockerfile with the reference one. For doing so, execute the following commands.
<br>`rm -rf ~/Source/Spark/image/centos/Dockerfile`{{execute}}
<br>`cp ~/test/Dockerfile ~/Source/Spark/image/centos/`{{execute}}

To view the content of the file, execute the following
`cat ~/Source/Spark/image/centos/Dockerfile`{{execute}}

Copy the configure jupyter file.<br>
`cp ~/test/configure_jupyter.sh ~/Spark/image/centos`{{execute}}

Copy the configure java file.<br>
`cp ~/test/configure_java8.sh ~/Spark/image/centos`{{execute}}


