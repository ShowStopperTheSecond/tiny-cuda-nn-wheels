[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/cloudposse.svg?style=social&label=Follow%20%40Ashleigh%20Watson)](https://twitter.com/OutofAi) 

Support my channel:  <a href="https://www.buymeacoffee.com/outofai" target="_blank" ><img src="https://img.shields.io/badge/-buy_me_a%C2%A0coffee-red?logo=buy-me-a-coffee" align="center" alt="Buy Me A Coffee"></a>

This repository facilitates the creation of Python wheel files (.whl) from the [tiny-cuda-nn project](https://github.com/NVlabs/tiny-cuda-nn) to streamline the installation process on Google Colab.

_(All relevant credits and licenses are attributed to Nvidia. The materials and software licenses from the original tiny-cuda-nn repository are not included in this repository. Please refer to the original project for licensing details.)_

Google Colab Usage:

For T4 GPU
```
!curl -L "https://github.com/tiny-cuda-nn-wheels/tiny-cuda-nn-wheels/releases/download/1.7/tinycudann-1.7.post75-cp310-cp310-linux_x86_64.whl" -o tinycudann-1.7.post75-cp310-cp310-linux_x86_64.whl
!pip install tinycudann-1.7.post75-cp310-cp310-linux_x86_64.whl
import tinycudann as tcnn
```

For V100 GPU
```
!curl -L "https://github.com/tiny-cuda-nn-wheels/tiny-cuda-nn-wheels/releases/download/1.7/tinycudann-1.7.post70-cp310-cp310-linux_x86_64.whl" -o tinycudann-1.7.post70-cp310-cp310-linux_x86_64.whl
!pip install tinycudann-1.7.post70-cp310-cp310-linux_x86_64.whl
import tinycudann as tcnn
```

For A100 GPU
```
!curl -L "https://github.com/tiny-cuda-nn-wheels/tiny-cuda-nn-wheels/releases/download/1.7/tinycudann-1.7.post89-cp310-cp310-linux_x86_64.whl" -o tinycudann-1.7.post89-cp310-cp310-linux_x86_64.whl
!pip install tinycudann-1.7.post89-cp310-cp310-linux_x86_64.whl
import tinycudann as tcnn
```
