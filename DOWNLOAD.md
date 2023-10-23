Dataset **OD-WeaponDetection: Pistol Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/u/s/7D/KW6uZRe5L716vu2eEXrEe4l4J7U9tprpf1ysRcyBbgYDSQVHcsfltY3Wktpe0WKgLvTC4IVFRzda6WR92DHlfCWClWA7dZk3WZg4uC7ujJ9yqclBy6Z4SrvGB5jp.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='OD-WeaponDetection: Pistol Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

