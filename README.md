# MyAwesomeInfraStack

Lista de recursos interessantes para as ferramentas que utilizo, principalmente voltada a infraestrutura como código, contendo links para roles do Ansible, modulos do Terraform e coisas do tipo, assim como informacoes interessantes sobre infra como um todo.

## Monitoring

### Prometheus

> Prometheus is an open-source systems monitoring and alerting toolkit originally built at SoundCloud.
> https://prometheus.io/

**Ansible**

- Prometheus
https://github.com/cloudalchemy/ansible-prometheus

- AlertManager
https://github.com/cloudalchemy/ansible-alertmanager

- Exporters
https://github.com/cloudalchemy/ansible-blackbox-exporter
https://github.com/cloudalchemy/ansible-node-exporter

As roles de exporter da **CloudAlchemy** tambem servem como uma boa base para outros exportadores baseadas em Golang (geralmente, a grande maioria).

### Grafana

> Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share dashboards with your team and foster a data driven culture.
> https://grafana.com/

Uma excelente companhia ao Prometheus.

**Ansible**

https://github.com/cloudalchemy/ansible-grafana