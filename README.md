# kubie-manifest
Kubernetes config for my EC2 instance that holds my project backends.

Jenkins server receives git pushes -> builds docker image -> pushes docker image to docker hub -> kubies

<br />Dockerfile's FROM: needs to match node's OS