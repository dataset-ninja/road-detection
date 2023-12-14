Dataset **Road Detection and Centerline Extraction** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/3/9/SU/IEZKWQvWz25brP6omp9oysA99X8z8cEnRD0V2JaF73xyTGUhh2k1WzRAuOzN7iyAXFOuWwP2yWmzCBa7evlGiZpDBjdMoTj2JcyVXcrL8kh4B7FfJKPdeuQqo2h9.tar)

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