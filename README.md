# ansible-operator-poc

## Working example of ansible-operator created using operator-sdk v0.19.2( works on s390x)

This operator creates a deployment of busybox(excuse the name nginx, nginx doesn't run on openshift without tinkering with SCCs).
The no. of replicas and image tag can be manipulated thru the CR.
