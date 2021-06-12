# Platform centric structure

This deployments repo structure is platform centirc. It uses the unified path -  ***path::[Platform]/[Method]/[Component]/<deployment manifest/tool>***

Pros -
1. More intuitive to DevOps teams that are platform/method centric e.g. ECS/cloudformtaoin or K8s/helm
2. DevOps team can navigate and download the deployments manifests/tools without an understanding of the architecture 

Cons -
1. Requires a separation between Aqua Cloud and Aqua Enterprise. In fact, Aqua Cloud is a subset of Aqua Enterprise limited to enforcers and the scanner
2. Need to maintain duplicate folders and manifest files between Aqua Cloud and Aqua Enterprise 


