# AWS_Architecting-using-Lucidchart B

## Description:  Architecture on Building &amp; Distributing new AMIs in the AWS Cloud

### Point to Note: Before going through this repository,make sure you have well understood AWS_Architecting_with_Lucidchart.

<p> As we all know,the Lucidchart provides collaborative online diagramming to make it easy to draw flowcharts in real time thus helping teams to see and build the future from idea to reality.

<P> In the AWS cloud, finely tuned, well-architected infrastructure plans helps the cloud to scale to their full potential.</p>

Architectures helps your team to monitor, secure, automate, and optimize resources.
For AWS cloud servers, a great way to avoid these kinds of technical constraints on your team is by building a “Golden AMI pipeline”, that establishes a baseline configuration for acceptable EC2 instances by each of your organization’s business units. This can prove to be especially useful when your organization has several development teams that don’t communicate, but need to comply by the same security and compliance standards. With this pipeline in place, individual teams can move more quickly and autonomously.

<P>In the Manual Process 

  At a high-level overview, the process for building and distributing new AMIs are as follows:

### Step 1

<P> .From the lucid chart,you will select the AWS Cloud,which you will drag and drop
     
    .create an EC2 server using an existing AMI as the base image.In this process,it will be a drag and drop too as well
  
### Step 2
  
<P>  .Drag and drop a configured instance to meet application or management requirements, e.g. setting up SSH, logging, or installing the latest software updates
  Your image should look like this below;
  
![code image](https://user-images.githubusercontent.com/103466963/174665649-e5b33915-a976-458a-8740-29d632ad3cf2.png)

### Step 3
  
<P> Drag and drop link ups to create and distribute a new AMI from the configured instance
  
### Step 4
  
<p> On the chart, Rollout each EC2 server or AutoScaling Group that requires the new AMI
  
  See diagrams below:
  
  ![image builder](https://user-images.githubusercontent.com/103466963/174667063-36b7faae-d16b-43c9-9476-11ff59ec4857.png)

  ![ami architecture](https://user-images.githubusercontent.com/103466963/174667146-780c3328-eced-4051-874c-4753702b558e.jpeg)
