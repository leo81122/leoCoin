# leoCoin
#### envs:
* golang 12.5

----
## 2019.12.22

> - 修改生成当前hash值为工作量证明(POW))方式
> - 增加Block.Diff成员，使用difficult来判断hash前多少位为0，而不是在mine()中写死
> - 在验证函数中加入根据当前difficult验证hash前difficult位是否为0  
#### TBD
> - 后续加入转账、网络化功能

------

## 2019.11.13
> - 当前已经完成大概框架
#### TBD
> - 后续继续加入工作量证明、网络化等工作 

------
