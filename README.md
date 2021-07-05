1. The first is the automatic restart of the pods. You need to carefully review the manifest, and change the parameters (namespace, schedule, deployment name, tolerations) to your own.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2. The second is the automatic distribution of an https certificate using cert-manager and let's encrypt. Before adding the manifest, you need to install the cert-manager. 
   And also in the manifest, you need to change the parameters (email, tolerations, hosts) to your own.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
