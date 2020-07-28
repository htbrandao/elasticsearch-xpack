# # [Elastic](https://www.elastic.co/guide/en/elasticsearch/reference/7.8/secure-settings.html#secure-settings) docs

# # [Kibana](https://www.elastic.co/guide/en/kibana/7.8/docker.html) docs

# # How to

- Run a elastic container with `xpack.security.enabled: false`
- `bin/elasticsearch-certutil ca`
- `bin/elasticsearch-certutil cert --ca elastic-stack-ca.p12` # previous output
- Set the parameters on `elasticsearch.yml` as the one on this project # i.e: xpack parameters
- `bin/elasticsearch-setup-passwords auto`
- log into elasticsearch and kibana using the **`elastic`** super user
