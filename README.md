In order to run this config files in the docker server

Make changes in the promtail.yaml file : 

1. In the client change the url from "localhost" to the "hostIP"  --> this helps in connecting the promtail to loki
2. In the target change the "localhost" to the "hostIP"
