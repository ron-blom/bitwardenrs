# BitWardenRS
This project is part of my [homeserver](https://github.com/ron-blom/homeserver) project and will deploy a bitwardenrs on my homeserver.

Using images: 

bitwardenrs/server


persistent storage:
```
/data
```

# Deploy 

```
helm secrets upgrade --install bitwardenrs-chart ./bitwardenrs-chart -f bitwardenrs-chart/secrets.yaml
```