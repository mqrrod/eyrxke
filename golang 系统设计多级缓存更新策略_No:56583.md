最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计多级缓存更新策略
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.5jji69.asia/arts/940514.Doc

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.5jji69.asia/arts/646288.Doc

原标题：看懂报错日志快速定位问题
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.5jji69.asia/arts/861628.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.5jji69.asia/arts/415403.Doc

原标题：全局本地依赖隔离冲突规避
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.5jji69.asia/arts/073828.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.5jji69.asia/arts/647201.Doc

原标题：macOS 脚本执行权限开启
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.5jji69.asia/arts/383511.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://wiki.5jji69.asia/arts/449857.Doc

原标题：Practice：实现接口防重提交组件实践
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.5jji69.asia/arts/185588.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.5jji69.asia/arts/723033.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.5jji69.asia/arts/923804.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.5jji69.asia/arts/593929.Doc

原标题：包管理器依赖缓存清理
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.5jji69.asia/arts/835785.Doc

原标题：golang 系统设计版本号语义化规范讲解
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.5jji69.asia/arts/345092.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/416873.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.5jji69.asia/arts/129998.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.5jji69.asia/arts/156885.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://wiki.5jji69.asia/arts/827363.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.5jji69.asia/arts/599184.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.5jji69.asia/arts/505167.Doc

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.5jji69.asia/arts/990252.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.5jji69.asia/arts/307585.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.5jji69.asia/arts/230581.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.5jji69.asia/arts/344252.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.5jji69.asia/arts/819965.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.5jji69.asia/arts/498236.Doc

原标题：git rebase 整理提交历史实操
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.5jji69.asia/arts/907133.Doc

原标题：golang mysql 死锁排查步骤讲解
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.5jji69.asia/arts/293791.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.5jji69.asia/arts/459692.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.5jji69.asia/arts/269272.Doc

原标题：前端静态缓存更新生效处理
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.5jji69.asia/arts/208956.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.5jji69.asia/arts/999551.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.5jji69.asia/arts/054875.Doc

原标题：golang mysql 连接泄漏检测方法
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.5jji69.asia/arts/001377.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.5jji69.asia/arts/266589.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.5jji69.asia/arts/901811.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.5jji69.asia/arts/047328.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.5jji69.asia/arts/984887.Doc

原标题：golang redis set 集合去重业务
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.5jji69.asia/arts/260074.Doc

原标题：golang http 请求重试封装工具
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.5jji69.asia/arts/674370.Doc


二、踩坑排错｜Troubleshooting
原标题：主干开发团队代码合并策略
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.5jji69.asia/arts/163528.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.5jji69.asia/arts/800915.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.5jji69.asia/arts/215738.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.5jji69.asia/arts/358662.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.5jji69.asia/arts/278007.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.5jji69.asia/arts/799188.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.5jji69.asia/arts/425778.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.5jji69.asia/arts/019441.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.5jji69.asia/arts/896528.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.5jji69.asia/arts/756776.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.5jji69.asia/arts/307200.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.5jji69.asia/arts/378148.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.5jji69.asia/arts/232730.Doc

原标题：golang 系统设计布隆过滤器原理与落地
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.5jji69.asia/arts/075798.Doc

原标题：golang redis 缓存更新策略讲解
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.5jji69.asia/arts/648691.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.5jji69.asia/arts/561391.Doc

原标题：Docker Compose 一键搭建本地栈
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.5jji69.asia/arts/522958.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.5jji69.asia/arts/493363.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.5jji69.asia/arts/642777.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.5jji69.asia/arts/203260.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.5jji69.asia/arts/181458.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.5jji69.asia/arts/088955.Doc

原标题：开源项目本地运行排错完整清单
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.5jji69.asia/arts/630688.Doc

原标题：eslint prettier 代码规范落地
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.5jji69.asia/arts/802822.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.5jji69.asia/arts/193781.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.5jji69.asia/arts/601929.Doc

原标题：方案对比：缓存更新策略Cache‑Aside读写模式
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.5jji69.asia/arts/375573.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.5jji69.asia/arts/873747.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.5jji69.asia/arts/616952.Doc

原标题：K8s 镜像拉取网络故障修复
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.5jji69.asia/arts/271451.Doc

原标题：进程线程并发基础概念讲解
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.5jji69.asia/arts/651623.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.5jji69.asia/arts/307600.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.5jji69.asia/arts/537921.Doc

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.5jji69.asia/arts/249391.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.5jji69.asia/arts/745724.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.5jji69.asia/arts/271396.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.5jji69.asia/arts/203298.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.5jji69.asia/arts/568628.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.5jji69.asia/arts/393987.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.5jji69.asia/arts/652840.Doc

三、实战开发｜Practice
原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.5jji69.asia/arts/084069.Doc

原标题：golang yaml 解析配置加载实操
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.5jji69.asia/arts/745711.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.5jji69.asia/arts/830258.Doc

原标题：多规则数据脱敏组件开发
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.5jji69.asia/arts/263527.Doc

原标题：golang 系统设计回调重试幂等完整处理
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.5jji69.asia/arts/882782.Doc

原标题：Cookie Session 会话状态管理
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.5jji69.asia/arts/560626.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.5jji69.asia/arts/145662.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.5jji69.asia/arts/881062.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.5jji69.asia/arts/892525.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.5jji69.asia/arts/579165.Doc

原标题：golang redis 热点 key 业务规避
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.5jji69.asia/arts/019025.Doc

原标题：golang websocket 消息广播实现
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.5jji69.asia/arts/452798.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.5jji69.asia/arts/591214.Doc

原标题：golang channel 通道并发处理
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.5jji69.asia/arts/899805.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.5jji69.asia/arts/890137.Doc

原标题：golang docker 部署 es 本地开发
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.5jji69.asia/arts/636170.Doc

原标题：文件批量导入导出功能实现
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.5jji69.asia/arts/630742.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.5jji69.asia/arts/366167.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.5jji69.asia/arts/417408.Doc

原标题：前后端会话登录状态持久化
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.5jji69.asia/arts/453142.Doc

原标题：简易网关请求路由过滤模拟
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.5jji69.asia/arts/671175.Doc

原标题：golang 系统设计监控缺失指标补全完整流程
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.5jji69.asia/arts/112505.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.5jji69.asia/arts/381867.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.5jji69.asia/arts/093401.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://wiki.5jji69.asia/arts/352683.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.5jji69.asia/arts/385383.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.5jji69.asia/arts/912513.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.5jji69.asia/arts/652405.Doc

原标题：golang 系统设计文件存储选型对比
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://wiki.5jji69.asia/arts/485535.Doc

原标题：文件读写与异常捕获代码示例
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.5jji69.asia/arts/201466.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.5jji69.asia/arts/649891.Doc

原标题：golang 数据库慢查询监控实现
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://wiki.5jji69.asia/arts/578064.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.5jji69.asia/arts/126818.Doc

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.5jji69.asia/arts/447950.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.5jji69.asia/arts/272654.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.5jji69.asia/arts/931509.Doc

原标题：配置外部化线上部署防错误
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.5jji69.asia/arts/882976.Doc

原标题：express 请求参数校验处理
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.5jji69.asia/arts/892823.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.5jji69.asia/arts/648570.Doc

原标题：Performance：JSON序列化性能优化实践
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.5jji69.asia/arts/415457.Doc

四、架构设计｜Architecture
原标题：布隆过滤器数据高效去重实现
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://wiki.5jji69.asia/arts/007162.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.5jji69.asia/arts/977984.Doc

原标题：golang 系统设计并发控制协程池任务池实现
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.5jji69.asia/arts/114690.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.5jji69.asia/arts/860596.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.5jji69.asia/arts/568697.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.5jji69.asia/arts/345256.Doc

原标题：从零学习基础的接口请求与参数处理
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.5jji69.asia/arts/706811.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.5jji69.asia/arts/623557.Doc

原标题：golang 表单文件大小限制配置
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.5jji69.asia/arts/330985.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.5jji69.asia/arts/239443.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.5jji69.asia/arts/455925.Doc

原标题：从零搭建本地数据库开发环境
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.5jji69.asia/arts/971639.Doc

原标题：monorepo 项目多包管理最佳实践
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.5jji69.asia/arts/711792.Doc

原标题：Git 混乱提交历史清理方法
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://wiki.5jji69.asia/arts/886995.Doc

原标题：golang validator 自定义校验规则
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.5jji69.asia/arts/380172.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.5jji69.asia/arts/464369.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.5jji69.asia/arts/536844.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.5jji69.asia/arts/344682.Doc

?
