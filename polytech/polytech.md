---
layout: page
title: Polytech BIT services
---

I have worked with the Dev Ops project team to keep The BIT service up and running. 
This was a struggle as the documentation left to us was not of the best, or maybe the documentation needed updated by a previous team that failed to do so or that the some of the steps involved have changed.

I will work with rob over the holiday period to restore the media analytic website as this was my doing. While I may have found the problem was that I rebooted the server hoping that it would restart the system however this did not happen as it did not bring the service up. And the documentation on this on the [wiki]( https://gitlab.com/op-bit-platform/OPS-and-Security-Wiki/-/wikis/Media-Analytics/Useful%20Commands).

  ![image]({{site.github.url}}/assets/img/workingThroughGitlab-ci.JPG)
  <img src="{{ site.github.url }}/asset/img/workingThroughGitlab-ci.JPG" alt="" title=""width="1000" />

I have looked into this as the MA site. I have looked at the gitlab-ci.yml file and try and replicate the commands used to serve this site but came into trouble that the ip for the database connection was not working as it should and I showed the result to the team who then looked into other vm servers and found that in fact that it was a rogue serve as this ip address was used as a system administration assignment vm. So that seemed to be a problem but also I can’t use what was in the wiki because the gitlab.op-bit.nz site which we handle is down and can’t access it to try their fix and could not run the runner on the serve as there are certificate errors with gitlab.

A problem is im not sure if I do have the right access/group to the vm sphere and I do not know how to access the gateway and iss server as they are windows based and the other servers are linux/ubuntu I believe which I can access with a public private key and they are located on the gitlab.com. I am a guest and can not change the wiki on the op bit platform

{{site.github.url}} this should be 

















I have worked with our project team to keep our services working. While this was difficult as documentation for creating and placing the neces

I did work on eliminating the git-lab server unessasary ticketing while I did not fix the issue I think I had stopped that particular check from happening and that seemed to stop the tickets but also mathew did update the amount of ram for that server


Working with Media-analytics site

I added a code and did not no how to restart the website so i restarted the machine. while i thought that would bring this back up it did not. I have been searching the web and through the bash history of the ma server and have found some commands used and found where the nginx is looking for the website




