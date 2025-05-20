# Jenkins_Assignment 
###**Easy:**
In this Assignment we are just exploring and trying the basic features of Jenkins like what does jenkins do and how to use it and all.
So basically you can install Jenkins Application in a docker container using this command
```sh
docker run -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```
You will now run the jenkins in your docker container just access jenkins by following the lead and once you open jenkins it looks like this
<img src="images/Picture-1.png" alt="Repository Creation" width="800">

Now we have to create a new Job named Hello_Jenkins to just understand the basics of Jenkins
Create a new Job and then create and select a Pipeline  and add some description and then proceed to the pipeline code which is written in the .groovy file extension and click on save
 <img src="images/Picture-2.png" alt="Repository Creation" width="800">
 
 <img src="images/Picture-3.png" alt="Repository Creation" width="800">
 
<img src="images/Picture-4.png" alt="Repository Creation" width="800">

After this press on build to get the pipeline to be built

<img src="images/Picture-5.png" alt="Repository Creation" width="800">

After pressing build It looks something like this

<img src="images/Picture-6.png" alt="Repository Creation" width="800">

For successful Execution we can check the console output by selecting it

<img src="images/Picture-7.png" alt="Repository Creation" width="800">

As we can see its success which means it got executed without any errors.
We can Also see the Pipeline overview by selecting an option in the Jobs

<img src="images/Picture-8.png" alt="Repository Creation" width="800">

Now we have to add some changes into Pipeline by selecting configure in the jobs sections

<img src="images/Picture-9.png" alt="Repository Creation" width="800">

The change we are adding is cleanup stage in the pipeline groovy program.

<img src="images/Picture-10.png" alt="Repository Creation" width="800">

After adding the change press save and build it to get 2# build with updated change 

<img src="images/Picture-11.png" alt="Repository Creation" width="800">

<img src="images/Picture-12.png" alt="Repository Creation" width="800">

We can Observe the change in the Pipeline as we have added another stage in it.

<img src="images/Picture-13.png" alt="Repository Creation" width="800">


###**End Of Assignment**
