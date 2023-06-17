Dataset **Cattle Face Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/p/R/xz/aSyEjdv5wtrcG1SbLKNc5D7qEAv6I4GhSaiMgnIsxVW0Kvr4fj2vVvbpgzeFrScPdNy76vdSEsR3LKa1IyyzcEVehAjvFskPocO3ioPcYUMOk8RQ1rnFl1neFNMS.tar)

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