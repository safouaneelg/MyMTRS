# SyMTRS

<<<<<<< HEAD
## Super Resolution

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x2 --hr_root /home/data/SyMTRS/hr --model srcnn --scale 2 --out_dir sr_runs_srcnn_x2
```

or in background
```bash
nohup python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x2 --hr_root /home/data/SyMTRS/hr --model srcnn --scale 2 --out_dir sr_runs_srcnn_x2 > sr_runs_srcnn_x2/train.log 2>&1 &
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x4 --hr_root /home/data/SyMTRS/hr --model srcnn --scale 4 --out_dir sr_runs_srcnn_x4
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x8 --hr_root /home/data/SyMTRS/hr --model srcnn --scale 8 --out_dir sr_runs_srcnn_x8
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x2 --hr_root /home/data/SyMTRS/hr --model autoencoder --scale 2 --out_dir sr_runs_autoencoder_x2 --num_workers 0
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x4 --hr_root /home/data/SyMTRS/hr --model autoencoder --scale 4 --out_dir sr_runs_autoencoder_x4
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x8 --hr_root /home/data/SyMTRS/hr --model autoencoder --scale 8 --out_dir sr_runs_autoencoder_x8
```

```bash
nohup python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x2 --hr_root /home/data/SyMTRS/hr --model srgan --scale 2 --out_dir sr_runs_srgan_x2   > sr_runs_autoencoder_x2/train.log 2>&1 &
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x4 --hr_root /home/data/SyMTRS/hr --model srgan --scale 4 --out_dir sr_runs_srgan_x4
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x8 --hr_root /home/data/SyMTRS/hr --model srgan --scale 8 --out_dir sr_runs_srgan_x8
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x2 --hr_root /home/data/SyMTRS/hr --model swinir --scale 2 --num_workers 0 --out_dir sr_runs_swinir_x2
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x4 --hr_root /home/data/SyMTRS/hr --model swinir --scale 4 --out_dir sr_runs_swinir_x4
```

```bash
python train_superresolution.py --lr_root /home/data/SyMTRS/lr/x8 --hr_root /home/data/SyMTRS/hr --model swinir --scale 8 --out_dir sr_runs_swinir_x8
```

## Gen AI

```bash
mkdir -p genai_runs/vae genai_runs/dcgan genai_runs/diffusion
```

```bash
nohup python train_moncular_depth.py --model zoe_n --rgb /home/data/SyMTRS/hr --depth /home/data/SyMTRS/depth --out_dir monodepth_runs --datasplit_seed 42 > monodepth_runs/zoe_n/train.log 2>&1 &
```

```bash
nohup python train_moncular_depth.py --model unidepth_s --rgb /home/data/SyMTRS/hr --depth /home/data/SyMTRS/depth --out_dir monodepth_runs --datasplit_seed 42 > monodepth_runs/unidepth_s/train.log 2>&1 &
```

```bash
nohup python train_moncular_depth.py --model midas_s --rgb /home/data/SyMTRS/hr --depth /home/data/SyMTRS/depth --out_dir monodepth_runs --datasplit_seed 42 > monodepth_runs/midas_s/train.log 2>&1 &
```
=======
Comming soon ...
>>>>>>> d5124d9ee3cddfa141d7df44a39e6664ef5d10fe

