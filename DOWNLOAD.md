Dataset **Cattle Face Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/p/C/Kz/LPanFStkZlpSDjh2hBlvuoFW7wzQAgUNkClY0SlLfqTqSdenQrBRyQEQhcEtrRhFJsTMZ2zm48ULK3gHCKKhYPK0YHeUVfmJsyxUKmcpwihBOyA1El2ziqi9Ge8T.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Cattle Face Detection', dst_path='~/dtools/datasets/Cattle Face Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/universidade-federal-de-santa-maria-dbq3m/cattle-face-detection/dataset/1/download)