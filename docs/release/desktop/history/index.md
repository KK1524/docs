# 当前版本

## 0.1.7.0 咕咕咕 <Badge text="预览版" type="warning" vertical="middle" />

[下载](https://file.xunkong.cc/download/desktop/package/Xunkong.Desktop.Package_0.1.7.0_x64.msixbundle)
2022-04-11 016:48:28

咕了这么久的祈愿记录导出功能终于来喽，同时也增加了表格预览的功能，这次使用了 Syncfusion 的表格控件，功能很强大性能很糟糕，每1000条记录加载需要1.5s，所以默认不开启表格显示。

深渊记录有了单独的显示界面，总算把呆在设置页面的**保存深渊记录**按键给去掉了。能从米游社获取的深渊数据比我想象的要少，出战次数只有最多的四个角色，战斗记录只有每间的最后一次，当初设想的很多分析维度都没法实现。

新增了一个数据库自动备份功能，关闭寻空时如果发现距离上一次备份超过7天，就会自动复制数据库到备份文件夹 `我的文档\Xunkong\Backup\Database`，再也不怕误操作数据丢失了。

接下来的版本将努力优化性能。。。（感觉很难做到）

### 更新内容

- 新增
  - 深境螺旋记录
  - 祈愿记录管理
  - 数据库清理及压缩功能
  - 数据库自动备份（每周一次）
  - 启动应用时自动签到 [#75](https://github.com/Scighost/Xunkong/issues/75)
- 删除
  - 祈愿记录页面的导入功能（移至 工具箱 > 祈愿记录管理）
  - 祈愿记录页面的元数据更新提醒（启动应用后会自动更新）
- 更改
  - 点击更新提醒的下载按键后不再直接下载文件，而是打开此页面