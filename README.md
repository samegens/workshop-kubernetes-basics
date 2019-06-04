# Manifests voor de Workshop Kubernetes basics

Dit zijn de manifest files die gebruikt zijn tijdens de workshop. De volgorde is:
1. [pod](pod)
2. [rs](rs) (ReplicaSet)
3. [svc](svc) (Service)
4. [deploy](deploy) (Deployment)
5. [ingress](ingress)

Om de resources uit te rollen:

    kubectl apply -f <path to yml> --record
  