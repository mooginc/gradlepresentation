# Copy files
1. Copy the files in the data directory to the build directory
2. Copy foo.txt from the data directory to the build directory
3. Same as 2, but extend to copy bar.txt to another directory

### Execution
From the root dir execute the following command line:
```gradlew :Labs:CopyFiles:yourtaskname```

Alternatively load the build file directly
```gradlew -b Labs/CopyFiles yourtaskname```
