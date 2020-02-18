# Pytorch_BN_Fold
Batch Normalization Folding (Fusion of Conv and BN) in Pytorch
Fuse Convolution and Batch Noramlization even if they are not in seqeuntial block.

```
fused_net = fuse_bn_recursively(net)
```

@Reference : https://github.com/MIPT-Oulu/pytorch_bn_fusion/blob/master/bn_fusion.py
