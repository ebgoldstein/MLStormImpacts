# Washover
Classifier for detecting washover in post-storm images

### Data
- Post-storm images from NOAA (Downloaded via [`psi-collect`](https://github.com/UNCG-DAISY/psi-collect))
- Classifications from Hurricane Florence (data [here](https://doi.org/10.6084/m9.figshare.11604192.v1))
- Extra data from Hurricane Michael (Testing) and Hurricane Isaias (testing)

### Code
- mobilenet v1 (only FC tuned, imagenet weights)
- VGG16 (only FC tuned, imagenet weights)
