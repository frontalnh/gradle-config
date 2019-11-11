# Getting started

```sh
gradle init
```

## Basic Concept

### Task

A Task represents a single atomic piece of work for build, such as compiling classes or generating javadoc.
Each task belongs to Project. You can use the various methods on TaskContainer to create and lookup task instance. For example TaskContainer.create(java.lng.String) creates an empty task with the given name. You can also use the task keyword in your build file

