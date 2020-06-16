---
layout: page
title: Polytech BIT services
---

I have worked with the Dev Ops project team to keep The BIT service up and running. 
This was a struggle at times because of the documentation left to us was not the best, or maybe the documentation needed updated by a previous team that failed to do so or that the some of the steps involved have changed with updated systems.
<br />

I will work with rob over the holiday period to restore the media analytic website as this was my doing. While I may have found the problem was that I rebooted the server hoping that it would restart the system however this did not happen as it did not bring the service up. And the documentation on this on the [wiki]( https://gitlab.com/op-bit-platform/OPS-and-Security-Wiki/-/wikis/Media-Analytics/Useful%20Commands).
<br />

![image]({{site.github.url}}/assets/img/workingThroughGitlab-ci.JPG)
I have looked at the gitlab-ci.yml file and try and replicate the commands used to serve this site but came into trouble that the ip for the database connection was not working as it should and I showed the result to the team who then looked into other vm servers and found that in fact that it was a rogue serve as this ip address was used as a system administration assignment vm. So that seemed to be a problem but also I can’t use what was in the wiki because the gitlab.op-bit.nz site which we handle is down and can’t access it to try their fix and could not run the runner on the serve as there are certificate errors with gitlab.
<br />
  
![image]({{site.github.url}}/assets/img/sites-avaliable.JPG)
The above image show that the site runs of nginx and the location of the of it.
<br />
  

A problem is im not sure if I do have the right access/group to the vm sphere and I do not know how to access the gateway and iss server as they are windows based and the other servers are linux/ubuntu I believe which I can access with a public private key and they are located on the gitlab.com. I am a guest and can not change the wiki on the op bit platform
<br />
  

There was a message on Teams about a dependancy porblem 
![image]({{site.github.url}}/assets/img/dependancyProblem.png)
some of the communication of the problem 
![image]({{site.github.url}}/assets/img/dependancyProblemComunication.png)
with the fix that i had researched with the problem being similar. I implemented the solution but didn't get much feed back from the member as to if it worked or not, or if it wasn't the correct way of fixing it. So I guess that no news it seemed to work.
<br />
 
<br />
 
![image]({{site.github.url}}/assets/img/helped.JPG)
 The above image is of our systems administrator giving us a problem from one of our lectures, it turns out that I had seen this, and I tried the site and it was working and I could log on with no problem so I thought what could be the problem. It was the url she had entered was wrong and it was bit-op and should have been op-bit. Problem solved quickly.
<br />

<br />

<br />
<br />
<br />
<br />
<br />
<br />
<br />


I have worked with our project team to keep our services working. While this was difficult as documentation for creating and placing the neces

I did work on eliminating the git-lab server unessasary ticketing while I did not fix the issue I think I had stopped that particular check from happening and that seemed to stop the tickets but also mathew did update the amount of ram for that server


Working with Media-analytics site

I added a code and did not no how to restart the website so i restarted the machine. while i thought that would bring this back up it did not. I have been searching the web and through the bash history of the ma server and have found some commands used and found where the nginx is looking for the website




