# ML Washover
This is the dev area for creating a classifier for detecting washover in post-storm images.
The cleaned version will live [here](https://github.com/UNCG-DAISY/WashoverML).

![WashGradCam](https://user-images.githubusercontent.com/5330599/91177308-839e2200-e6b1-11ea-916e-e4b7e544dacc.jpg)

### Data
- Post-storm images from NOAA (Downloaded via [`psi-collect`](https://github.com/UNCG-DAISY/psi-collect))
- Classifications from Hurricane Florence (data [here](https://doi.org/10.6084/m9.figshare.11604192.v1))
- Extra data from Hurricane Michael (Testing)

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
                        ├── Inception.ipynb
                        └── ...
                        
```
