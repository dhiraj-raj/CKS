# CKS
**Network Policies**

If you want to control traffic flow at the IP address or port level (OSI layer 3 or 4), then you might consider using Kubernetes NetworkPolicies for particular applications in your cluster. NetworkPolicies are an application-centric construct which allow you to specify how a pod is allowed to communicate with various network "entities" (we use the word "entity" here to avoid overloading the more common terms such as "endpoints" and "services", which have specific Kubernetes connotations) over the network


The file shown are different network policies applied between Frontend App $ Backebd App, also, defulat-deny.yaml restrict the communications between the pods for the given namespaces.
