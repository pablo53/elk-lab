# elk-lab
Elastic Stack Laboratory

## Security configuraion steps

### ElasticSearch Pod shell

> `/usr/share/elasticsearch/bin/elasticsearch-reset-password -u elastic`

> `/usr/share/elasticsearch/bin/elasticsearch-create-enrollment-token -s kibana`

### Kibana Pod shell

> `bin/kibana-setup --enrollment-token <enrollment-token>`
