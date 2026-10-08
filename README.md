# vsp-inversion
VSP 初至反演速度模型代码库
- vsp2ssp.m：VSP 转换波速度结构成像核心 Matlab 脚本，输出高分辨率地下速度剖面
- vsp_linear_inverse_problem.m：基于 SVD 分解与 Tikhonov 正则化的 VSP 线性走时反演脚本，适合基础速度模型构建
- step1.m + step2.m：分步式 VSP 波速比计算与走时反演组合脚本，可输出纵横波速比参数辅助岩性判断
vsp2ssp-master.zip 运行结果为反演与成像
