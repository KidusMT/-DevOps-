# -DevOps-
Important resources..links found about the DevOps

The text file in the repository is the terminal history of the project I have been working in gebeya for different projects. The commands that I have used to create a kubernetes cluster and creating deployments, services, ingress and so much. 

## Keywords in this project
  - Kubernetes (k8s)
  - Jenkins
  - Deployments
  - Ingress
  - Services
  - Cluster
  - Pods
  - Gcloud
  - Helm
  - Docker
  - Mongodb

## Best DevOps CI/CD tools:
  - [codemagic - for all mobile platforms](https://codemagic.io/start/)
  - [appcenterms - for all mobile platforms](http://appcenter.ms/)

For automatic version increment on every push from stackoverflow [answer](https://stackoverflow.com/a/57879685/6021740) from [Andre Cytryn](https://stackoverflow.com/users/1165337/andre-cytryn)
From Codemagic [documentation][1] they show you a few options:

```
Here are some examples of the build arguments you can use to increment the app version. You can enter the build arguments in App settings > Build > Build arguments.

--build-name=2.0.$BUILD_NUMBER --build-number=$(($BUILD_NUMBER + 100))

--build-name=1.0.0 --build-number=$BUILD_NUMBER

--build-number=$(git rev-list HEAD --count)
```

Add it here:

[![enter image description here][2]][2]


> Please note that the number of builds in BUILD_NUMBER is counted
> separately for each workflow.


  [1]: https://docs.codemagic.io/building/build-versioning/
  [2]: https://i.stack.imgur.com/MU7we.png
