# 红果TV H700 稳定版更新源

本仓库用于 ANBERNIC H700（640×480）的 PORTS「红果TV」稳定版更新。

## 更新清单

- 启动脚本读取：`update.json`
- 更新包：Release `v0.3.0` 中的 `hongguo-tv-h700-stable.zip`
- 解压密码：`langos`
- 必须整包替换 `hgcore` + `hgui`，不要只换一个。

## 本版

- core `0.3.0-h700`
- 按 MP4 `stts/stsz` 分段时间线限速，预读 8 秒
- 不锁 720P，1080P-only 片源可播
- 1080P HEVC 30fps 实测稳定

## 校验

```
hgcore  bba04f559387e436df15c6eb7b61566647c97aa95ab0094e7877632d09bebd13
hgui    cf11a122f3a287def1722ab32f0d1670e5f55db62b6ae00e7701d7af016bf7be
zip     729f3271919a0e4e2853d3b8f9002c68bcdc20357db2f68cd7f4f3d3ece5bb11
```
