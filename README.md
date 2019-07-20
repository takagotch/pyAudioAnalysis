### pyaudioanalysis
---
https://github.com/tyiannak/pyAudioAnalysis

```py
from pyAudioAnalysis import audioTrainTest as aT
aT.featureAndTrain(["classifierData/music", "classifierData/speech"], 1.0, 1.0, aT.shortTermWindow, aT.shortTermStep, "svm", "svmSMtemp", False)
aT.fileClassification("data/doremi.wav", "svmSMtemp", "svm")


@article{giannakopoulos2015pyaudionalysis,
  title={pyAudioAnalysis: An Open-Source Python Library for Audio Signal Analysis},
  author={Giannakopulos, Theodoros},
  journal={PloS one},
  volume={10},
  number={12},
  year={2015},
  publisher={Public Library of Science}
}
```

```sh
pip install numpy matplotlib scipy skearn hmmlearn simplejson eyed3 pydub
git clone https://github.com/tyiannak/pyAudioAnalysis.git
pip install -e .
```

```
```


