# FlavorClassPrediction
Flavor Class Prediction

Author: Yasushi Nakata, Organization for Research Promotion, Osaka Metropolitan University, Sakai, Osaka, 599-8531, Japan

Email: yasushi.nakata@omu.ac.jp.

DOI:

This repository accompanies the publication by Y. Nakata, "Flavor Prediction of Pyrazines Using Machine Learning" (now writing). 
The GCN model constructed above are available in 'model240610bk2.zip'.
As an example, we presented the notebook 'pred_radar.ipynb' using this GCN model for creation of thr radar chart of coffee in Figure 3a.

##Execution environment

- Python 3.11.12 of Google Colaboratory

with numpy 1.23.5, tensorflow 2.12.0, and Deepchem 2.8.1.dev
 
## Contents
- ```coffee_dataset.csv```: csv file with IUPACName CanonicalSMILES, and intensity data. Upload this file under directory '/content/drive/My Drive/'
- ```model240610bk2.zip```: After unzipping, upload the files under model directory '/content/drive/My Drive/model240610bk2'
- ```pred_radar.ipynb```: jupyternotebook for flavor class prediction

## Reference of coffee_dataset.csv
Refer to 'Table III. Normalized Peak Volumes' in the next.
- Cordero C, Liberto E, Bicchi C, Rubiolo P, Reichenbach SE, Tian X, et al. Targeted and non-targeted approaches for complex natural sample profiling by GC× GC-qMS. Journal of chromatographic science. 2010;48(4):251-61.


