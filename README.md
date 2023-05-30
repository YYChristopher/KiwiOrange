# KiwiOrange
AnimeGAN model have trained for DL groupWork.

Requirements:

- python 3.6
- tensorflow-gpu 1.15.0 (GPU 2080Ti, cuda 10.0.130, cudnn 7.6.0)
- opencv
- numpy
- argparse
- tqdm

Inference:

python test.py  --checkpoint_dir  checkpoint/generator_Hayao_weight  --test_dir dataset/test/HR_photo --save_dir save_dir
