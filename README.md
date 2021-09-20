
这是一份会长期更新和完善的 Go 学习指南和面试专题，会逐步进行完善。

欢迎到【[公众号](https://github.com/eddycjy/go777#%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7)】获取最新文章或加我 【[微信](https://github.com/eddycjy/go777#%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7)】提意见（记得 Star），可倒推煎鱼更新，感谢各位。

## Go 学习指南

- [跟煎鱼学 Go 语言（含 gin、grpc、grpc-gateway 实战）](https://eddycjy.com/go-categories/)
- [Go 语言编程之旅](https://golang2.eddycjy.com/)
- [Go 语言进阶之旅](https://golang1.eddycjy.com/)

## Go 模块管理

- [Go Modules 入门到熟练](https://mp.weixin.qq.com/s/6gJkSyGAFR0v6kow2uVklA)
- [Go Modules 历史、坑、技巧](https://mp.weixin.qq.com/s/jpp7vs3Fdg4m15P1SHt1yA)

## Go 面试专题

- [Go new 和 make 是什么，差异在哪？](https://mp.weixin.qq.com/s/tZg3zmESlLmefAWdTR96Tg)
- [Goroutine 数量控制在多少合适，会影响 GC 和调度？](https://mp.weixin.qq.com/s/uWP2X6iFu7BtwjIv5H55vw)
- [Go defer 闭包问题](https://mp.weixin.qq.com/s/lELMqKho003h0gfKkZxhHQ)
- [Go interface 的一个 “坑” 及原理分析](https://mp.weixin.qq.com/s/vNACbdSDxC9S0LOAr7ngLQ)
- [进程、线程都有 ID，为什么 Goroutine 没有 ID？](https://mp.weixin.qq.com/s/qFAtgpbAsHSPVLuo3PYIhg)
- [GMP 模型，为什么要有 P？](https://mp.weixin.qq.com/s/an7dml9NLOhqOZjEGLdEEw)
- [Go 结构体是否可以比较，为什么？](https://mp.weixin.qq.com/s/HScH6nm3xf4POXVk774jUA)
- [单核 CPU，开两个 Goroutine，其中一个死循环，会怎么样？](https://mp.weixin.qq.com/s/h27GXmfGYVLHRG3Mu_8axw)
- [你知道 Go 结构体和结构体指针调用有什么区别吗？](https://mp.weixin.qq.com/s/g-D_eVh-8JaIoRne09bJ3Q)
- [Goroutine 泄露的情况有哪些？](https://mp.weixin.qq.com/s/ql01K1nOnEZpdbp--6EDYw)
- [详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？](https://mp.weixin.qq.com/s/YK-TD3bZGEgqC0j-8U6VkQ)
- [Go 在什么时候会抢占 P？](https://mp.weixin.qq.com/s/WAPogwLJ2BZvrquoKTQXzg)
- [什么是协程，协程和线程的区别和联系？](https://mp.weixin.qq.com/s/vW5n_JWa3I-Qopbx4TmIgQ)
- [为什么 Go map 和 slice 是非线程安全的？](https://mp.weixin.qq.com/s/TzHvDdtfp0FZ9y1ndqeCRw)
- [Go 面试官问我如何实现面向对象？](https://mp.weixin.qq.com/s/2x4Sajv7HkAjWFPe4oD96g)
- [Go sync.map 和原生 map 谁的性能好，为什么？](https://mp.weixin.qq.com/s/8aufz1IzElaYR43ccuwMyA)
- [Go 是传值还是传引用？](https://mp.weixin.qq.com/s/qsxvfiyZfRCtgTymO9LBZQ)

## Go 历史版本特性

### 1.17

- [支持切片转换为数组指针](https://mp.weixin.qq.com/s/v1czjzlUsaSQTpAOG9Ub3w)
- [支持泛型了？具体怎么用](https://mp.weixin.qq.com/s/Pf7YuFpwbldSB60DDCBtlA)
- [支持模糊测试（Fuzzing）](https://mp.weixin.qq.com/s/zdsrmlwVR0bP1Q_Xg_VlpQ)
- [增强构建时的编译约束](https://mp.weixin.qq.com/s/5kLFIuI0UJl_o8vMmZNfoA)
- [优化 modules：支持模块依赖图裁剪、延时模块加载](https://mp.weixin.qq.com/s/2vVGVd_QJSrCeenuvwGS3g)
- [优化基于寄存器的函数参数和结果传递](https://mp.weixin.qq.com/s/cYnlPTM3R02_kZsIukmVfg)
- [优化恐慌所抛出的异常堆栈信息](https://mp.weixin.qq.com/s/zu5atVDYYaRIJ5sj96mlmg)

### 1.16
- [支持静态资源编译打包](https://mp.weixin.qq.com/s/aBPrBHl9BpbvbJyatB3Vww)
- [变更内存管理机制：从 MADV_FREE 改回 MADV_DONTNEED](https://mp.weixin.qq.com/s/l4oEJdskbWpff1E3tTNUxQ)
- [优化 modules：支持后悔药](https://mp.weixin.qq.com/s/0g89yj9sc1oIz9kS9ZIAEA)
- [逐步移除 GOPATH](https://mp.weixin.qq.com/s/uSqBCrRaSSR82aL0jw3TfQ)

## 常用软件

- HTTP
  - [gin](https://github.com/gin-gonic/gin)
- RPC
  - [grpc-go](https://github.com/grpc/grpc-go)
  - [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway)
- 微服务框架
  - [go-zero](https://github.com/tal-tech/go-zero)
  - [kratos](https://github.com/go-kratos/kratos)
- ORM
  - [gorm](https://github.com/go-gorm/gorm)
  - [xorm](https://gitea.com/xorm/xorm)

## 福利

待完善中...

- [在线资料](https://github.com/eddycjy/go-developer-roadmap/blob/main/docs/book/%E7%94%B5%E5%AD%90%E4%B9%A6.md#%E5%9C%A8%E7%BA%BF%E8%B5%84%E6%96%99)
- [电子书（请勿传播）](https://github.com/eddycjy/go777/blob/main/docs/book/%E7%94%B5%E5%AD%90%E4%B9%A6.md#go-%E8%AF%AD%E8%A8%80)
- 简历模板

## 我的公众号

所有文章和最新进度，请关注：

![image](https://image.eddycjy.com/7074be90379a121746146bc4229819f8.jpg)

关注公众号后，可回复 002 可获取我的个人微信号。

我拉你进 Go 读者交流群，连接数千位 Go 爱好者，共同学习和进行技术交流！
