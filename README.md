# wordpressdemo

This is a demo of OpenShift for students at Lernia education.



## WordPress

You need to create the PVC, and then mount it as /data. Start the Wordpress pod and copy files from /opt/app-root/src/ to /data.

Delete the wordpress pod and change Deployment configuration so it volume mounts the pvc in /opt/app-root/src/ folder instead.


