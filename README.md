1. EC2 add AMAZON_EBS_CSI_DRIVER into IAM role
- kubectl create secret generic mysql-pass --from-literal=password=eks-mysql-pw 
2. Execute kubectl apply -k "github.com/kubernetes-sigs/aws-ebs-csi-driver/deploy/kubernetes/overlays/stable/?ref=release-0.10"
3. kubectl apply -f .
