# Month 0 产出记录

## 报告

### BPI-F3 支持矩阵:

- [Fedora on BPI-F3](https://github.com/ruyisdk/support-matrix/tree/main/BPI-F3/Fedora) , [pr_merged](https://github.com/ruyisdk/support-matrix/commit/121e78c5149d3cf011a43afee1eec4bb0dc376e7)
- [OpenWrt on BPI-F3](https://github.com/ruyisdk/support-matrix/tree/main/BPI-F3/OpenWrt), [pr_merged](https://github.com/ruyisdk/support-matrix/commit/33cf00f1993cf3f59d682c9367c98441c0487fda)

### Milk-V Jupiter demos:

仓库: [Milk-V_Jupiter_Demos](https://github.com/Sharelter/Milk-V_Jupiter_Demos)

测试以下两个demo:

- [chatglm2-demo](https://github.com/Sharelter/Milk-V_Jupiter_Demos/blob/main/chatglm2.md)
- [llama3-demo](https://github.com/Sharelter/Milk-V_Jupiter_Demos/blob/main/llama3.md)

### Chromium 在RevOS上的可用性:

Chromium tests on Milk-V Pioneer with RevyOS:

- [Pioneer_RevyOS](https://github.com/QA-Team-lo/chromium_test/tree/main/p_re)

### openGauss 性能对比测试:

在openEuler-x86_64平台测试openGauss读写性能为Pioneer提供参考: :

- PR: [79ccdc0](https://github.com/QA-Team-lo/dbtest/commit/79ccdc05d5648db836c8af51beac56cfe4b43816)

##  系统镜像

### Milk-V DuoS 和 Duo256可用的Debian镜像:

- fixed ref sources and github action auto build script
- Link: [sophgo-sg200x-debian](https://github.com/Sharelter/sophgo-sg200x-debian)

## 玄铁课程评论任务

对两个 XuanTie [RISC-V Institute 课程](https://www.xrvm.cn/community/risc_v) 视频进行点评（见内部表格）

## 兴趣项目

为同事提供一些远程开发板资源，并构建了一个docker镜像来自动化创建远程访问跳板容器:

- [testing-infra-jumper-docker](https://github.com/Sharelter/testing-infra-jumper-docker)