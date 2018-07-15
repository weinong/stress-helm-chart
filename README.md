# stress-helm-chart

This is a helm chart based on https://hub.docker.com/r/progrium/stress/.

To use it, 
`helm upgrade ${RELEASE} stress-helm-chart --install --set stress.vm=1,stress.vmBytes=500M,replicaCount=3`
