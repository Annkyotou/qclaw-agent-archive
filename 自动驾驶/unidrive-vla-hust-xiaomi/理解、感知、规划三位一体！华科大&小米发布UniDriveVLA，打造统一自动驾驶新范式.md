---
title: "理解、感知、规划三位一体！华科大&小米发布UniDriveVLA，打造统一自动驾驶新范式"
source_platform: "微信公众号"
source_url: "#"
account_name: "深蓝AI"
publish_date: "2026年4月17日"
capture_date: "2026-04-23"
capture_method: "Playwright Headless Chromium"
images_count: 22
tags:
  - 自动驾驶
  - VLA
  - 华科大
  - 小米
  - 具身智能
  - AI
---

# 理解、感知、规划三位一体！华科大&小米发布UniDriveVLA，打造统一自动驾驶新范式

## 📌 文章概要

**来源**：微信公众号「深蓝AI」  
**发布**：2026年4月17日  
**主题**：理解、感知、规划三位一体！华科大&小米发布UniDriveVLA，打造统一自动驾驶新范式

---

## 📄 核心内容摘要

### 课题名称
**UniDriveVLA：理解-感知-规划三位一体的端到端自动驾驶视觉语言动作模型**

### 研究背景与痛点
当前自动驾驶方案普遍存在"模块化pipeline"问题：感知、预测、规划各自独立优化，模块间接口复杂、信息逐级损失，难以应对真实城市场景的的长尾挑战。同时，主流方案依赖高精地图，在地图覆盖薄弱区域性能骤降；数据闭环成本高，长尾场景（施工绕行、紧急躲避）获取困难。端到端自动驾驶（E2E AD）被视为破局方向，但如何让模型同时具备环境"理解"、实时"感知"和可解释"规划"能力仍是开放难题。

### 解决方案：VLA融合架构
UniDriveVLA（华科大&小米联合发布）提出"理解-感知-规划"三位一体架构：

- **视觉编码器**：多视角相机输入，通过ViT编码时空特征
- **大语言模型基座**：引入LLM的语义理解能力，让模型"读懂"场景（如交通标志含义、行人意图预测）
- **动作预测头**：输出可执行的控制指令（转向、加速、刹车）

| 技术亮点 | 具体实现 | 优势 |
|---------|---------|------|
| **端到端优化** | 感知→规划统一梯度回传 | 消除模块间误差累积 |
| **无图方案** | 实时建图+定位替代高精地图 | 降低成本，提升泛化性 |
| **可解释性** | 输出自然语言场景描述 | 便于安全审计与人为干预 |
| **数据闭环** | 自动标注+仿真回放 | 高效处理长尾场景 |

### 科学与工程价值
- **工程落地**：推动L4级自动驾驶从"Demo演示"走向"量产可落地"
- **学术贡献**：VLA范式验证了大模型与自动驾驶融合的可行性，为后续研究提供baseline
- **产业影响**：小米在智能驾驶领域的持续投入（对标特斯拉FSD）标志着中国车企加速追赶


> 公众号：深蓝AI | 发布时间：2026年4月17日

## 内容摘要

华中科技大学与小米联合发布UniDriveVLA，一个将理解、感知、规划统一建模的自动驾驶端到端系统。该架构在多个 benchmark 上刷新 SOTA，同时保持良好的可解释性。

## 图片存档

- ![img-01.jpg](images/img-01.jpg)
- ![img-02.jpg](images/img-02.jpg)
- ![img-03.jpg](images/img-03.jpg)
- ![img-04.jpg](images/img-04.jpg)
- ![img-05.jpg](images/img-05.jpg)
- ![img-06.jpg](images/img-06.jpg)
- ![img-07.jpg](images/img-07.jpg)
- ![img-08.jpg](images/img-08.jpg)
- ![img-09.jpg](images/img-09.jpg)
- ![img-10.jpg](images/img-10.jpg)
- ![img-11.jpg](images/img-11.jpg)
- ![img-12.jpg](images/img-12.jpg)
- ![img-13.jpg](images/img-13.jpg)
- ![img-14.jpg](images/img-14.jpg)
- ![img-15.jpg](images/img-15.jpg)
- ![img-16.jpg](images/img-16.jpg)
- ![img-17.jpg](images/img-17.jpg)
- ![img-18.jpg](images/img-18.jpg)
- ![img-19.jpg](images/img-19.jpg)
- ![img-20.jpg](images/img-20.jpg)
- ![img-21.jpg](images/img-21.jpg)
- ![img-22.jpg](images/img-22.jpg)
