# OpenStack-Notes

[Releases do OpenStack](https://github.com/raquel/openstack-notes/blob/master/releases.md)

Legenda:
- API* = API Documentada
-> Colocar Link para a documentação da API

### CONFIRMADOS

| PRIODIDADE | MÓDULO | DESCRIÇÃO SIMPLES | API* | Ports |
| --- | --- | --- |:---:| --- |
| 1 | NOVA | Compute | :heavy_check_mark: | 8774 |
| 1 | NEUTRON | Networking | :heavy_check_mark: | 9696 |
| 1 | SWIFT | Object Storage | :heavy_check_mark: | 8080 |
| 1 | CINDER | Block Storage | :heavy_check_mark: | 8776 |
| 1 | KEYSTONE | Identity | :heavy_check_mark: | 5000, 35357 |
| 1 | GLANCE | Image Service | :heavy_check_mark: | 9292 |
| 1 | HORIZON | Dashboard | :x: | N/A |
| 1 | CEILOMETER | Telemetry | :heavy_check_mark: | 8777 |
| 1 | HEAT | Orchestration | :heavy_check_mark: | 8004 |
| 1 | MURANO | Application Catalog | :x: | 8082 |
| 2 | AODH| Telemetry Alarming | :x: | |
| 2 | GNOCCHI | Times Series Database and Resource Indexing | :x: | |
| 2 | [MONASCA](https://github.com/raquel/openstack-notes/blob/master/Monasca.md) | Monitoring Service | :x: | |
| 2 | MANILA | Shared Filesystem | :heavy_check_mark: | |
| 2 | IRONIC | Bare-metal Provisioning | :heavy_check_mark: | |
| 2 | BARBICAN | Key Management Service | :x: | |
| 2 | MAGNUM | Container as a Service | :x: | |
| 2 | DESIGNATE | DNS as a Service | :x: | |
| 2 | CONGRESS | Governance Service | :x: | 1789 |
| 2 | TACKER | NFV Orchestration | :x: | |
| 3 | TROVE | Database as a Service | :heavy_check_mark: | 8779 |
| 3 | CLOUDKITTY | Rating and Billing Service | :x: | |
| 3 | ZAQAR | Messaging Service | :x: | |
| 3 | VITRAGE | Root Cause Analysis Engine | :x: | |
| 3 | WATCHER | Resource Optimization | :x: | |
| 3 | BLAZAR | Reservation Service | :x: | |
| 3 | RALLY | Benchmark Service | :x: | |
| 3 | FREEZER | Backup, Restore and Disaster Recovery Service | :x: | |
| 3 | SAHARA | Elastic Map Reduce | :heavy_check_mark: | |
| 3 | FUEL | Deployment Service | :x: | |
| 3 | KOLLA | Production-ready container and deployment | :x: | |
| 3 | MISTRAL | Workflow Service | :x: | |
| 3 | SENLIN | Clustering Service | :heavy_check_mark: | |
| 3 | SOLUM | Application Lifecycle Management Service | :x: | .|
