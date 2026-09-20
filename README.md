# 克隆仓库

当前版本的视频直接存储在 Git 中，无需安装 Git LFS：

```bash
git clone https://github.com/KK-Zhou/RMT.git
cd RMT
```

新增或替换视频时，每个文件必须小于 100 MiB，才能通过普通 Git 推送到 GitHub。
旧提交中的视频仍使用 LFS；检出这些旧版本需要 Git LFS。

# 本地查看网页
1. 终端执行以下命令启动本地服务器：
```bash
python3 -m http.server 8000
```
2. 打开浏览器访问
http://localhost:8000/

## Citation
If you find our paper or repositories helpful to your research, please consider citing the paper:
```
@article{
    
}
```
