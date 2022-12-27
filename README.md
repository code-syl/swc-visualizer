# SWC Visualizer

To use HTTPS, either generate a key and cert in `C:/certificates/swc-visualizer` or delete the following line in the `angular.json` file:

```json
73 >>>          "sslKey": "C:/certificates/swc-visualizer/localhost-key.pem",
74 >>>          "sslCert": "C:/certificates/swc-visualizer/localhost.pem"
```

To disable HTTPS, set the `ssl` key to `false` inside the same `angular.json`.
