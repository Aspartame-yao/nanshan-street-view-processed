# Nanshan Street View — Processed

南山区研究区街景清理与标准化结果。

## 数据内容

- 7,636 张处理后街景，与原始数据逐张对应
- 使用 `doubao-seedream-5.0-lite` 完成图像清理
- 统一为 1024×1024 JPEG
- 保留采样点 ID、WGS84 经纬度和方向信息

数据压缩包位于仓库的 **Releases** 页面；`MANIFEST.csv` 提供每个文件的相对路径、字节数和 SHA-256。

## 目录结构

```text
data/
└── <point_id>/
    └── <point_id>_<longitude>_<latitude>_<heading>.jpg
```

本仓库不包含模型调用脚本、API 密钥、访问令牌、请求日志或云存储凭据。

## 使用说明

原始影像的权利仍归相应权利人所有，处理结果不改变其权利状态。使用者需自行确认研究、展示和再分发权限。

