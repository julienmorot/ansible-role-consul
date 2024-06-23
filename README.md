# ansible-role-consul

## Role variables :

Possible configuration variables and default values are :

```
consul_datacenter: "dc1"
consul_data_dir: "/opt/consul"
consul_client_addr: "0.0.0.0"
consul_ui_config_enabled: "true"
consul_server: "true"
consul_bind_addr: "0.0.0.0"
consul_advertise_addr: Default IPV4 address
consul_bootstrap_expect: 3
consul_encrypt: "mp+JOIsXqlbi54HXdGQ7G/nzwfWi3CGI9vlaF1jTrRY="
```

You must define a unique encrypt key with consul keygen command.
