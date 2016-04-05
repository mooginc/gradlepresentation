# Download dependencies
1. Download a file http://www.thoughtcow.com/media/photologue/photos/chuck.jpg

Hint, the internal ant engine makes life easy here (https://ant.apache.org/manual/Tasks/get.html)
Attributes to the ant get task are function arguments in the ant.get call in gradle.

### Execution
From the root dir execute the following command line:
```gradlew :Labs:Download:yourtaskname```

Alternatively load the build file directly
```gradlew -b Labs/Download yourtaskname```
