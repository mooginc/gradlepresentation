# Build order
1. Create three tasks A, B and C
2. Create a fourth task 'all', which depends on A, B and C
3. Reverse the order of the task execution by setting the dependencies of the A, B And C tasks
4. Reverse the order of the tasks by controlling the [execution order](https://docs.gradle.org/current/userguide/more_about_tasks.html#sec:ordering_tasks)

### Execution
From the root dir execute the following command line:
```gradlew :Labs:BuildOrder:all```

Alternatively load the build file directly
```gradlew -b Labs/BuildOrder all```

