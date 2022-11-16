# snowid-service

a simple id generation service by snowid

## Usage

### Environment Variable

* `PORT`, port to listen
* `WORKER_ID`, unique worker id, if not set, will guess from hostname (Kubernetes StatefulSet Pod)

### Invocation

```
GET /healthz

OK
----------
GET /any/other/path?size=10

[
  "380651065730707456",
  "380651065730707457",
  "380651065730707458",
  "380651065730707459",
  "380651065730707460",
  "380651065730707461",
  "380651065730707462",
  "380651065730707463",
  "380651065730707464",
  "380651065730707465"
]
```

## Donation

Check https://guoyk.net/donation

## Credits

Guo Y.K., MIT License
