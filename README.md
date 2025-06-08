# ddp_example.py
ddp_example.py

執行以下指令進行訓練

```
$ CUDA_VISIBLE_DEVICES=0,1 python -m torch.distributed.launch --nproc_per_node=2 ddp_example.py
```
