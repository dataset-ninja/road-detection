Dataset **Road Detection and Centerline Extraction** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzMxMzFfUm9hZCBEZXRlY3Rpb24gYW5kIENlbnRlcmxpbmUgRXh0cmFjdGlvbi9yb2FkLWRldGVjdGlvbi1hbmQtY2VudGVybGluZS1leHRyYWN0aW9uLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIjROUUtTajJrMFRCRXM0UkJ2ZG9nTlI3OTRyUTBQZTJMT1kxVWQrOGtYRkE9In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Road Detection and Centerline Extraction', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/ipythonx/tgrs-road/download?datasetVersionNumber=1).