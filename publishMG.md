# 霸主小游戏更新版本流程
- 版本分支打小游戏版本分支
- 将上个版本的小游戏分支合并到当前分支
- 工具检查是否需要更新 wxgame.ts文件（guajiSkinrenderzidong WarriorZbPopSkin）
- 检查self书写
- 常规发布生成 gameEui.json文件，git上传
- 小游戏再发布一次
- svn update之后上传资源
- 更新小游戏文件

--------
# 原始RPK版本备注
- 华为线上版本-ys8_rpk; 包是在 ys10_rpk分支上维护的
- ys10rpk 已经被ys13合并了，（也就是ys10_rpk 和 ys13_rpk是一样的）
- 新版本需要测试：1.隐私协议 2.飘字是否显示

--------
# 如果更好的维护RPK分支？
- 备注各RPK的版本号（rpk_version.md）
- 如果各RPK包版本不一致，则在对应的版本分支上维护该rpk包，维护好后将老版本分支合并到最新的版本分支上
