# Image-Dehazing-using-DCP-alg
Image Dehazing using Dark Channel Prior (DCP) Algorithm
Overview
This project implements an image dehazing technique based on the Dark Channel Prior (DCP) algorithm. Hazy images often suffer from reduced visibility due to the scattering of light by particles in the atmosphere. The DCP algorithm is a widely recognized method for effectively removing haze and restoring clarity to images.

The DCP algorithm leverages the observation that in most non-sky patches of haze-free outdoor images, some pixels have very low intensity in at least one color channel (dark pixels). This prior is used to estimate the thickness of the haze and subsequently recover the haze-free image.
