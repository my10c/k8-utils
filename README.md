# k8-utils

Various Kubernetes scripts

### Kubernetes Registry
NOTES:

 - need to add the secret with:
```
 docker secret create my.crt certs/my.crt
 docker secret create my.key certs/my.key
```

 - adjust the variables to your need
```
	_my_port=						PORT TO USE
	_my_data_dir=					DIRECTORY/PARTITION FOR THE DOCKER REGISTRY
	_registry_auth_htpasswd_path=	THE AUTH FILE, SIMPLE
	_registry_http_addr=			LISTEN ADDRESS AND PORT
	_registry_http_tls_certificate=	CERT FOR SSL/HTTPS
	_registry_http_tls_key=			CERT KEY FOR SSL/HTTPS
```

enjoy

- momo
