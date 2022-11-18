
# Install OADP-operator

This YAML will install the OADP-operator into your cluster.


## install-oadp-operator-okd.yaml

This will install the OADP-operator in the OKD cluster.
You will be able to find it under Installed Operators in the Console (webui).

```bash
  $ oc apply -f install-oadp-operator-okd.yaml
```

## install-oadp-operator-ocp.yaml

Same as for OKD, but this one is for OCP. The difference is the source, 
for OKD it is "community-operators" and for OCP it is "redhat-operators".

NOTE: This (OCP) installation has not been tested yet.

```bash
  $ oc apply -f install-oadp-operator-ocp.yaml
```



