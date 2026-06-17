# Detectron2

- github source: https://github.com/facebookresearch/detectron2

- CUDA on the computer should be compatible with the version of CUDA that pytorch is compiled, which means that 11.x, 12.x, 13.x, ... are usually incompatible! 

- Modified compared to v0.6.0:

  - detectron2/data/transforms/transform.py
    - line - 46, Image.LINEAR -> Image.BILINEAR

- Installation:

  ```shell
  pip install -r requirements.txt
  pip install --no-build-isolation -e .
  ```
