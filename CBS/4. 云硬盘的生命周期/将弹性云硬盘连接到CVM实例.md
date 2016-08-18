[非弹性云硬盘]()在创建时自动挂载至创建的 CVM 实例上，同时用户可以手动将[弹性云硬盘]()挂载到同一可用区中的任意实例上，您可以在挂载时确定每个实例还能挂载多少云硬盘。有关挂载数量的更多信息，请参阅[使用约束]()。

## 使用控制台将弹性云硬盘挂载到实例
目前支持对作为<font color="red">数据盘</font>的普通弹性云硬盘云盘进行挂载，不可挂载系统盘。

1. 登录[腾讯云控制台](https://console.qcloud.com/)。

2. 进入【云服务器】-【云硬盘】选项卡。

3. 在云硬盘列表页，点击状态为<font color="red">待挂载、支持挂载/卸载</font>的云硬盘后的【更多】-【挂载到云主机】按钮进行单盘挂载；
或在云硬盘列表页，勾选状态为<font color="red">待挂载、支持挂载/卸载</font>的云硬盘，点击顶部【挂载】按钮进行批量挂载。

4. 在弹出框中选择需要挂载到的云服务器，点击【确定】按钮，等待挂载完毕即可登录云服务器查看云硬盘挂载状况。

云硬盘在挂载完后并不能马上使用，需要进行分区、格式化等一系列操作。具体操作方式请见：[Windows系统数据盘分区及格式化](http://www.qcloud.com/doc/product/213/Windows%E4%BA%91%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%95%B0%E6%8D%AE%E7%9B%98%E5%88%86%E5%8C%BA%E5%92%8C%E6%A0%BC%E5%BC%8F%E5%8C%96)、[Linux系统数据盘分区及格式化（MBR）](http://www.qcloud.com/doc/product/213/%E4%BD%BF%E7%94%A8MBR%E5%88%86%E5%8C%BA%E8%A1%A8%E5%88%86%E5%8C%BA%E5%B9%B6%E6%A0%BC%E5%BC%8F%E5%8C%96)、[Linux系统数据盘分区及格式化（GPT）](http://www.qcloud.com/doc/product/213/%E4%BD%BF%E7%94%A8GPT%E5%88%86%E5%8C%BA%E8%A1%A8%E5%88%86%E5%8C%BA%E5%B9%B6%E6%A0%BC%E5%BC%8F%E5%8C%96)

## 使用 API 将弹性云硬盘挂载到实例
请参考 [AttachCbsStorages 接口](https://www.qcloud.com/doc/api/364/2520)。