---
title: 以下在arthas中执行的
date: 2026-08-17 03:03:13
categories:
  - 技术
tags:
  - 技术
---

```bash
--查找最繁忙的前10个
thread -n 10
--看最忙的第一个在干嘛
thread 771
--显示这个方法的内部调用耗时情况
trace com.qlteacher.service.training.impl.TrainingUserServiceImpl getTrainingUserForCache
--对这个方法的执行情况进行一下统计
monitor com.qlteacher.service.training.impl.TrainingUserServiceImpl getTrainingUserForCache
--最终找到有问题的方法
trace com.qlteacher.service.training.impl.TrainingUserServiceImpl getProjectLessonInfoByChosen
```



