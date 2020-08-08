# Washover
Classifier for detecting washover in post-storm images

### Data
- Post-storm images from NOAA (Downloaded via [`psi-collect`](https://github.com/UNCG-DAISY/psi-collect))
- Classifications from Hurricane Florence (data [here](https://doi.org/10.6084/m9.figshare.11604192.v1))
- Eventually, include USGS iCoast data [Morgan et al.,](https://doi.org/10.5066/P93A9MPE)

### Code
- basic CNN
- mobilenet v1 (full retrain)
- VGG16 (fine-tuned, imagenet weights)
