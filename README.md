# [Submission for NTIRE 2024 Challenge on Image Super-Resolution (x4)](https://cvlai.net/ntire/2024/) @ [CVPR 2024](https://cvpr.thecvf.com/)

## How to test the proposed model?

1. `git clone https://github.com/hxu160/Submission-for-NTIRE-2024-SR-x4-.git`
2. Select the model you would like to test from [`run.sh`](./run.sh)
    ```bash
    CUDA_VISIBLE_DEVICES=0 python test_demo.py --data_dir [path to your data dir] --save_dir [path to your save dir] --model_id 16
    ```
    - Be sure the change the directories `--data_dir` and `--save_dir`.
    - We provide one model (team16): team16_augmented_swinfir. The code and pretrained model are provided.
    - The pretrained model can also be downloaded with [link](https://drive.google.com/file/d/1ldLPCJHnzdMypMCStNQZHq_MR9uAMRBb/view?usp=sharing).
    - We include some additional code (row 168-173 and row 270-274) in the test_demo.py to pad the input. 

## License and Acknowledgement
This repo is heavily built on the [SwinFIR code](https://github.com/Zdafeng/SwinFIR) and the [official template](https://github.com/zhengchen1999/NTIRE2024_ImageSR_x4). 

This code repository is release under [MIT License](LICENSE).