# crossplane-demo

Just run `./demo`, it should:
1. create a `kind` cluster
2. install `croseplane` core to your kind cluster
3. install the `provider-aws` of `crossplane` to your kind cluster
4. create a `eks` controlplane via the `crossplane`
5. output the `eks` cluster's kubeconfig at `./eks-kubeconfig`


**Note** To make sure this task is mainly focues on creating eks cluster, I did the following steps on AWS console directly
```
1. created the AMI role with EKS polciy on AWS console
2. created a default security group for VPC created by the `./demo`
```
