# Kubernetes Demo 

This directory contains the demo files used at the Workshop:

"Microservice-Architekturen praktisch am Beispiel Kubernetes"

at Software Architecture Summit 2018 on 12/3/2018.

## The Kubernetes Yaml files

|File                        | Usage                                          | 
|----------------------------|------------------------------------------------| 
| nginx.yaml                 | One pod of nginx                               | 
| 5_nginx.yaml               | scaled to 5 instances                          | 
| service_5_nginx.yaml       | now includes a service                         | 
| rolling_update_nginx.yaml  | rolling update to a new version                | 
| recreate_update_nginx.yaml | update using recreate                          | 
| create_config.sh           | creating a configMap that points to www folder | 
| www                        | this folder containing a very simple website   | 
| config_nginx.yaml          | running nginx with the configMap               | 
| external_service.yaml      | creating a service with ExternalName Type      | 
| diagnose.yaml              | running a diagnose container for looking into the cluster|  
