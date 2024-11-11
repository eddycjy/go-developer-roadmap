
这是一份会长期更新和完善的 Go 学习指南和面试专题，会逐步进行完善。

欢迎到【[公众号](https://github.com/eddycjy/go777#%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7)】获取最新文章或加我 【[微信](https://github.com/eddycjy/go777#%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7)】提意见（记得 Star），可倒推煎鱼更新，感谢各位。

## Go 学习路线图

![image](./image/go-developer-roadmap.png)

## LeetCode 算法全题解

和好朋友整理了一份 LeetCode 全题解，非常赞！可以关注我的【[公众号](https://github.com/eddycjy/go777#%E6%88%91%E7%9A%84%E5%85%AC%E4%BC%97%E5%8F%B7)】后回复 【000】 获取 PDF 版本。

覆盖大中厂常见算法题，共包含 700 道：

![image](./image/leetcode170.jpg)

## Go 学习指南

- [Go 语言入门系列：初探 Go 项目实战（含 gin、grpc、grpc-gateway 实战）](https://eddycjy.com/go-categories/)
- [Go 语言编程之旅：深入用 Go 做项目](https://golang2.eddycjy.com/)
- [Go 语言设计哲学：了解 Go 的为什么和设计思考](https://golang3.eddycjy.com/)
- [Go 语言进阶之旅：进一步深入 Go 源码](https://golang1.eddycjy.com/)


## Go 模块管理

- [Go Modules 入门到精通](https://mp.weixin.qq.com/s/6gJkSyGAFR0v6kow2uVklA)
- [Go Modules 历史、坑、技巧](https://mp.weixin.qq.com/s/jpp7vs3Fdg4m15P1SHt1yA)

## Go 面试专题

### 基本理解
- [Go 是传值还是传引用？](https://mp.weixin.qq.com/s/qsxvfiyZfRCtgTymO9LBZQ)
- [Go 面试官问我如何实现面向对象？](https://mp.weixin.qq.com/s/2x4Sajv7HkAjWFPe4oD96g)
- [你知道 Go 结构体和结构体指针调用有什么区别吗？](https://mp.weixin.qq.com/s/g-D_eVh-8JaIoRne09bJ3Q)
- [Go new 和 make 是什么，差异在哪？](https://mp.weixin.qq.com/s/tZg3zmESlLmefAWdTR96Tg)
- [什么是协程，协程和线程的区别和联系？](https://mp.weixin.qq.com/s/vW5n_JWa3I-Qopbx4TmIgQ)

### 调度模型
- [GMP 模型，为什么要有 P？](https://mp.weixin.qq.com/s/an7dml9NLOhqOZjEGLdEEw)
- [Go 结构体是否可以比较，为什么？](https://mp.weixin.qq.com/s/HScH6nm3xf4POXVk774jUA)
- [单核 CPU，开两个 Goroutine，其中一个死循环，会怎么样？](https://mp.weixin.qq.com/s/h27GXmfGYVLHRG3Mu_8axw)
- [进程、线程都有 ID，为什么 Goroutine 没有 ID？](https://mp.weixin.qq.com/s/qFAtgpbAsHSPVLuo3PYIhg)
- [Goroutine 数量控制在多少合适，会影响 GC 和调度？](https://mp.weixin.qq.com/s/uWP2X6iFu7BtwjIv5H55vw)
- [详解 Go 程序的启动流程，你知道 g0，m0 是什么吗？](https://mp.weixin.qq.com/s/YK-TD3bZGEgqC0j-8U6VkQ)
- [Goroutine 泄露的情况有哪些？](https://mp.weixin.qq.com/s/ql01K1nOnEZpdbp--6EDYw)
- [Go 在什么时候会抢占 P？](https://mp.weixin.qq.com/s/WAPogwLJ2BZvrquoKTQXzg)
- [会诱发 Goroutine 挂起的 27 个原因](https://mp.weixin.qq.com/s/h1zrFLWoryA7P5I19kwkpg)

### 数据结构

#### interface
- [Go interface 的一个 “坑” 及原理分析](https://mp.weixin.qq.com/s/vNACbdSDxC9S0LOAr7ngLQ)

#### defer
- [Go defer 闭包问题](https://mp.weixin.qq.com/s/lELMqKho003h0gfKkZxhHQ)

#### map/slice
- [为什么 Go map 和 slice 是非线程安全的？](https://mp.weixin.qq.com/s/TzHvDdtfp0FZ9y1ndqeCRw)
- [Go sync.map 和原生 map 谁的性能好，为什么？](https://mp.weixin.qq.com/s/8aufz1IzElaYR43ccuwMyA)
- [为什么 Go map 的负载因子是 6.5？](https://mp.weixin.qq.com/s/nL7jkskVHTmCy3Ed9e-RZA)


## 常见坑
- [Go slice append 数据异常](https://mp.weixin.qq.com/s/kEQI74ge6VhvNEr1d3JW-Q)

## 代码调试
- [学会使用 Go Delve 调试](https://mp.weixin.qq.com/s/Yz_p0S5N4ubf8wxLm5wbmQ)
- [学会使用 GDB 调试 Go 代码](https://mp.weixin.qq.com/s/O9Ngzgg9xfHMs5RSK5wHQQ)


## 官方资料
- [Go 编程语言规范](https://go.dev/ref/spec)
- [标准库介绍和文档](https://pkg.go.dev/std)
- [Go 博客](https://go.dev/blog/)
- [Go 邮件讨论组](https://groups.google.com/g/golang-nuts)
- [Effective Go](https://go.dev/doc/effective_go)
- [Go 实操之旅](https://go.dev/tour/welcome/1)
- [Go 泛型入门](https://go.dev/doc/tutorial/generics)

## 常用软件

- HTTP
  - [gin](https://github.com/gin-gonic/gin)
  - [echo](https://github.com/labstack/echo)
  - [iris](https://github.com/kataras/iris)
  - [GoFrame](https://github.com/gogf/gf)
- RPC
  - [grpc-go](https://github.com/grpc/grpc-go)
  - [grpc-gateway](https://github.com/grpc-ecosystem/grpc-gateway)
  - [rpcx](https://github.com/smallnest/rpcx)
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


## Go 历史版本特性

### 1.23
- [新标准库 unique，性能更好，开销更小](https://mp.weixin.qq.com/s/NDqeknAm7q77siHm0Jbcxg)
- [花了近 10 年，time.After 终于不泄漏了](https://mp.weixin.qq.com/s/Qcpj7TqMeOwCs--59kD3Kw)
- [time.Reset 解决了过期时间值的坑](https://mp.weixin.qq.com/s/NijdOmdfKGLJowhbe9yqPg)
- [争议最大的 iter 迭代器，可遍历万物](https://mp.weixin.qq.com/s/In_CxhOikw3iZYBnEXgG_g)
- [可以记录未捕获的 panic 和 throw 日志了](https://mp.weixin.qq.com/s/D16riVBbnDibLueQBIQ6Pw)
- [新库 structs.HostLayout，可以指定内存布局了](https://mp.weixin.qq.com/s/6YXi3g5stIWXxIj11qw6wA)
- [禁用 //go:linkname，建立新的握手机制](https://mp.weixin.qq.com/s/9waTxAhLH7yGkRM3kcQUOQ)
- [slices、panic、cookie 等函数改进，效率提高了](https://mp.weixin.qq.com/s/z5G7woc8_Rw2EKFWPxld_Q)

### 1.22
- [增强 http.ServerMux 路由能力](https://mp.weixin.qq.com/s/gGr1aM1ijBmaejfwW2qqeA)
- [for 循环不再共享循环变量，支持整数范围](https://mp.weixin.qq.com/s/OnvniPEvDz6k5LLKGH1MFA)
- [for 循环为什么要支持整数范围](https://mp.weixin.qq.com/s/cw7p2EuUTIj1TAcfCdfbew)
- [Slices 变更 Concat、Delete、Insert 等函数](https://mp.weixin.qq.com/s/z886NFcGeKkNm97YhBhc7w)
- [新的 math/rand/v2 库](https://mp.weixin.qq.com/s/BsZeSDxHwwSzjLjfjUIgIA)
- [性能提高、Trace 大修、工作区支持 vendor 等](https://mp.weixin.qq.com/s/_RHDJ1VGfqolE_Uzorosbw)

### 1.21
- [slices、maps 泛型库](https://mp.weixin.qq.com/s/1NuBnk8_lxmTi9N0biLa2g)
- [for 循环变量的语义变更](https://mp.weixin.qq.com/s/VO0VlfGbuvZst9yD73-VDQ)
- [context 可设置取消原因和回调函数](https://mp.weixin.qq.com/s/3HVmCkPdEBsM0W3dRh8ycw)
- [主版本号支持第三位数字 0](https://mp.weixin.qq.com/s/BfW8Ra3tsv7Dv3nu3MeI0g)
- [统一标准 log/slog](https://mp.weixin.qq.com/s/ZOdasSP0paVCLF94Vf9A9A)
- [支持自定义 go.env 文件](https://mp.weixin.qq.com/s/NR-yy9BWrs3qjvmO5Gd2CQ)
- [增强约束 Go 程序构建](https://mp.weixin.qq.com/s/s13EBwOExsVz_vwNEm0fvQ)
- [新内置函数和标准库 clear、min、max、cmp](https://mp.weixin.qq.com/s/MorBUrzpKFhssiZWLt4o6g)
- [panic(nil) 成为历史](https://mp.weixin.qq.com/s/xgJ8lPS-O84Ttne5heRa3g)
- [结束对 macOS 10.13/10.14 和 Windows 7/8、Server 2008/2012](https://mp.weixin.qq.com/s/s8ehvGK4tIOUcOqbKSI4Rg)
- [进一步支持 WASI](https://mp.weixin.qq.com/s/RNrO9U6wZkuGQgLtUJXuFQ)

### 1.20
- [两个关于 Time 的更新，不用背 2006-01-02 15:04:05 了](https://mp.weixin.qq.com/s/nBLBnh_NGh_XoN9HZh3XSw)
- [手动管理内存：arena 来了](https://mp.weixin.qq.com/s/6w0YO5l3_69A9z3KRYEizA)
- [arena 能手动管理内存了，怎么用](https://mp.weixin.qq.com/s/mwWMOwLsiY8EtODpyEoTIg)
- [PGO 是啥，咋就让 Go 更快更猛了](https://mp.weixin.qq.com/s/7uobN6DmpIYqG34pOpvvlA)
- [小修小补 errors 库 Unwrap](https://mp.weixin.qq.com/s/gfUM4EjE1av_YBeUBFyKtA)
- [禁止匿名接口循环导入](https://mp.weixin.qq.com/s/1d4XUoW5e45jYeEJEWoXeQ)
- [修改全局变量的初始化顺序](https://mp.weixin.qq.com/s/rtEhjJhwdkX3U01vHG6S8g)
- [SliceHeader 和 StringHeader 将会被废弃](https://mp.weixin.qq.com/s/al5zXILiKnqnsh-XrLMB6A)

### 1.19 
- [国产芯片、内存模型、性能提高等新特性](https://mp.weixin.qq.com/s/4L3qREFQo0rkZn9m5gabdw)

### 1.18
- [多 Module 工作区模式](https://mp.weixin.qq.com/s/Aa9s_ORDVfzbj915aJD5_w)
- [编译后的二进制文件，将包含更多信息](https://mp.weixin.qq.com/s/GWORgffT-xGNEwtOs_4llw)
- [新增好用的 Cut 方法](https://mp.weixin.qq.com/s/anYHPw46gONF1J_Mzg3cpg)
- [引入新的 netip 网络库](https://mp.weixin.qq.com/s/-6apXq9ZpBAK0FVDnY77xA)
- [被折腾 N 次的 TryLock](https://mp.weixin.qq.com/s/mHf2g7SIBRUC1a7UfDlwpw)
- [弃用 strings.Title 方法，换个新坑吧！](https://mp.weixin.qq.com/s/UiP-up751_Q3N0xzE2qkfA)
- [高效复制，strings, bytes 标准库新增 Clone API](https://mp.weixin.qq.com/s/QvyjBwKM12Ruz_stujVA7Q)

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

## 我的公众号

所有文章和最新进度，请关注：

![image](https://image.eddycjy.com/7074be90379a121746146bc4229819f8.jpg)

关注公众号后，可回复 002 可获取我的个人微信号。

我拉你进 Go 读者交流群，连接数千位 Go 爱好者，共同学习和进行技术交流！
