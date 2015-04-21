# Polyvia

<a href="https://github.com/baidu-ife/ife">百度 IFE 项目</a>高级班第 5 题

## 题目要求

### Low Poly 生成器

#### 任务描述

- 通过上传的图片，自动生成 Low Poly（低多边形）图像
- 提供手动指定边缘和特征点，来提高生成图片的效果

#### 任务要求

- 产品体验流畅

#### 任务目的

基于前端技术做图像领域的深入研究

## 完成功能

- [ ] 核心算法
  - [ ] 边缘检测
  - [ ] 人脸特征点识别
  - [ ] 图像预处理
  - [x] Delaunay 三角化
- [ ] 交互处理及效果展示
  - [ ] 上传图片
  - [ ] 边缘点展示
  - [ ] 人脸特征点展示
  - [ ] 边缘点修改
  - [ ] 特征点修改
  - [ ] 三角形渲染
- [ ] 附加功能（预案）
  - [ ] WebGL 加速卷积操作
  - [ ] 开启本地摄像头，实时处理视频

## 使用的第三方库

### ironwallaby / delaunay

Fast Delaunay Triangulation in JavaScript.

https://github.com/ironwallaby/delaunay


