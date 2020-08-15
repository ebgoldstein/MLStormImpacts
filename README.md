# Washover
Classifier for detecting washover in post-storm images

### Data
- Post-storm images from NOAA (Downloaded via [`psi-collect`](https://github.com/UNCG-DAISY/psi-collect))
- Classifications from Hurricane Florence (data [here](https://doi.org/10.6084/m9.figshare.11604192.v1))
- Extra data from Hurricane Michael (Testing) and Hurricane Isaias (testing)

### Code 
_(all models -- only FC layers tuned, imagenet weights)_
- Mobilenet V1
- Mobilenet V2
- Inception-Resnet
- Inception V3


### Directory Structure:

Should look like:

```{sh}
Users/ebgoldstein/MLWashover
                    ├── readme.md
                    ├── license
                    ├── data
                    │   ├── raw
                    │   ├── training                  
                    │   │    ├── nowashover
                    │   │    │     ├── C26047788.jpg
                    │   │    │     └── ...
                    │   │    └── washover
                    │   ├── validation
                    │   └── testing
                    └── src
                        ├── PictureSplitter.ipynb
                        ├── Mobilenet.ipynb
                        ├── VGG16.ipynb
                        └── ...
                        
```
