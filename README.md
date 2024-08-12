# Jenkins

## Jenkins slowness problem -> To solve this follow below steps 
```
cd /var/lib/jenkins/
sudo vi jenkins.model.JenkinsLocationConfiguration.xml  # Replace the current jenkins URL
sudo service jenkins restart
```
As Shown in image just replace your current jenkinsURL
![Screenshot 2024-08-12 084945](https://github.com/user-attachments/assets/4ffd182b-5668-471b-8c87-b625b3a4ecd4)

```
<?xml version='1.1' encoding='UTF-8'?>
<jenkins.model.JenkinsLocationConfiguration>
  <adminAddress>address not configured yet &lt;nobody@nowhere&gt;</adminAddress>
  <jenkinsUrl>http://13.235.90.125:8080/</jenkinsUrl>     # Replace here, with your current jenkins URL
</jenkins.model.JenkinsLocationConfiguration>

```



