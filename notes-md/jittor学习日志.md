# jittor学习日志

## 11/16/2025

```python
import jittor as jt
jt.flags.use_cuda =1
```

**保险起见，每次import jittor as jt以后都添加jt.flags.use_cuda=1**

jittor的环境检测在部件版本较多时无法合理检测，会被退回CPU模式，通过添加命令来强制使用CUDA和cuDNN