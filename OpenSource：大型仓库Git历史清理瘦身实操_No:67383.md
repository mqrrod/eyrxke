最新前沿技术资讯

一、入门教程｜Getting Started
原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.n5ict0.asia/arts/099525.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.n5ict0.asia/arts/091841.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.n5ict0.asia/arts/512545.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.n5ict0.asia/arts/276478.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.n5ict0.asia/arts/688119.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.n5ict0.asia/arts/170369.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.n5ict0.asia/arts/715675.Doc

原标题：golang url 参数编码处理方案
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/317629.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.n5ict0.asia/arts/132077.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.n5ict0.asia/arts/571411.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.n5ict0.asia/arts/665363.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.n5ict0.asia/arts/868199.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/706917.Doc

原标题：golang prometheus 告警规则编写
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.n5ict0.asia/arts/370945.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.n5ict0.asia/arts/847951.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.n5ict0.asia/arts/354556.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.n5ict0.asia/arts/457375.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.n5ict0.asia/arts/362161.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.n5ict0.asia/arts/249907.Doc

原标题：golang redis 热点 key 业务规避
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.n5ict0.asia/arts/784929.Doc

原标题：异步编程 Promise 执行流程解析
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.n5ict0.asia/arts/492737.Doc

原标题：golang redis 计数器防超卖示例
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.n5ict0.asia/arts/554526.Doc

原标题：端口占用访问失败排查方案
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.n5ict0.asia/arts/276218.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.n5ict0.asia/arts/357057.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.n5ict0.asia/arts/501744.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.n5ict0.asia/arts/712327.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.n5ict0.asia/arts/776250.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.n5ict0.asia/arts/787491.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.n5ict0.asia/arts/834974.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.n5ict0.asia/arts/638301.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.n5ict0.asia/arts/434409.Doc

原标题：golang prometheus 指标暴露实现
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.n5ict0.asia/arts/320347.Doc

原标题：从零学习简单分布式ID生成思路
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.n5ict0.asia/arts/729819.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.n5ict0.asia/arts/887382.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.n5ict0.asia/arts/603550.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.n5ict0.asia/arts/745607.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.n5ict0.asia/arts/462137.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.n5ict0.asia/arts/471352.Doc

原标题：golang redis 过期 key 监听业务
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.n5ict0.asia/arts/042787.Doc

原标题：golang es 索引生命周期管理思路
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.n5ict0.asia/arts/630139.Doc


二、踩坑排错｜Troubleshooting
原标题：react hooks 常见陷阱避坑指南
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.n5ict0.asia/arts/463033.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.n5ict0.asia/arts/977156.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.n5ict0.asia/arts/347524.Doc

原标题：golang minio 对象存储接口开发
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.n5ict0.asia/arts/667612.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.n5ict0.asia/arts/022122.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/836107.Doc

原标题：从零学习基础的接口请求与参数处理
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.n5ict0.asia/arts/565546.Doc

原标题：限流窗口绕过漏洞修复方案
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.n5ict0.asia/arts/037413.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.n5ict0.asia/arts/360545.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.n5ict0.asia/arts/440927.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.n5ict0.asia/arts/160548.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://wiki.n5ict0.asia/arts/480929.Doc

原标题：golang k8s liveness readiness 探针
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.n5ict0.asia/arts/666208.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.n5ict0.asia/arts/805284.Doc

原标题：golang redis 缓存雪崩完整处理
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.n5ict0.asia/arts/577354.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.n5ict0.asia/arts/767374.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.n5ict0.asia/arts/410366.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.n5ict0.asia/arts/005920.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.n5ict0.asia/arts/252893.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.n5ict0.asia/arts/354054.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://wiki.n5ict0.asia/arts/547158.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.n5ict0.asia/arts/709650.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.n5ict0.asia/arts/369978.Doc

原标题：golang http grpc 全链路埋点示例
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/228526.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.n5ict0.asia/arts/344946.Doc

原标题：入门实战：搭建简易静态网页项目
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.n5ict0.asia/arts/491961.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.n5ict0.asia/arts/517564.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.n5ict0.asia/arts/344803.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.n5ict0.asia/arts/743414.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.n5ict0.asia/arts/225792.Doc

原标题：Fork 开源项目同步上游代码
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.n5ict0.asia/arts/123568.Doc

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.n5ict0.asia/arts/090976.Doc

原标题：Git 误删提交代码恢复找回
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.n5ict0.asia/arts/008134.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.n5ict0.asia/arts/214806.Doc

原标题：定时任务周期调度 demo 开发
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.n5ict0.asia/arts/932929.Doc

原标题：golang kafka 核心概念分区副本
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.n5ict0.asia/arts/787561.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.n5ict0.asia/arts/562497.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.n5ict0.asia/arts/039533.Doc

原标题：golang 内存缓存简单实现方案
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.n5ict0.asia/arts/407470.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.n5ict0.asia/arts/698019.Doc

三、实战开发｜Practice
原标题：设计思考：API网关和BFF职责边界划分
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.n5ict0.asia/arts/994509.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.n5ict0.asia/arts/833051.Doc

原标题：线程调度优化减少上下文切换
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.n5ict0.asia/arts/084407.Doc

原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.n5ict0.asia/arts/080317.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.n5ict0.asia/arts/787323.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.n5ict0.asia/arts/826034.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.n5ict0.asia/arts/142373.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.n5ict0.asia/arts/001589.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/594766.Doc

原标题：golang mysql 分表 id 路由逻辑
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.n5ict0.asia/arts/174721.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.n5ict0.asia/arts/855300.Doc

原标题：golang redis stream 消息队列实践
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/337376.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.n5ict0.asia/arts/702710.Doc

原标题：golang 工具函数库封装思路
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.n5ict0.asia/arts/656299.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.n5ict0.asia/arts/166287.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.n5ict0.asia/arts/785424.Doc

原标题：JSON XML 数据解析处理示例
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.n5ict0.asia/arts/026286.Doc

原标题：axios 二次封装请求拦截处理
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.n5ict0.asia/arts/893162.Doc

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.n5ict0.asia/arts/482027.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.n5ict0.asia/arts/500466.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.n5ict0.asia/arts/673250.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.n5ict0.asia/arts/131805.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.n5ict0.asia/arts/553649.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.n5ict0.asia/arts/609130.Doc

原标题：Git 分支切换合并删除完整操作
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.n5ict0.asia/arts/451031.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.n5ict0.asia/arts/033766.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.n5ict0.asia/arts/742602.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.n5ict0.asia/arts/971821.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.n5ict0.asia/arts/324716.Doc

原标题：OpenAPI 自动接口文档生成
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.n5ict0.asia/arts/328563.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.n5ict0.asia/arts/977404.Doc

原标题：JWT 工具封装令牌刷新过期
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.n5ict0.asia/arts/762589.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://wiki.n5ict0.asia/arts/849550.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://wiki.n5ict0.asia/arts/796741.Doc

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.n5ict0.asia/arts/085073.Doc

原标题：定时任务周期调度 demo 开发
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.n5ict0.asia/arts/380849.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.n5ict0.asia/arts/319398.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.n5ict0.asia/arts/742143.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.n5ict0.asia/arts/807110.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.n5ict0.asia/arts/107364.Doc

四、架构设计｜Architecture
原标题：Hands‑on：简易网关路由转发组件开发
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.n5ict0.asia/arts/022583.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.n5ict0.asia/arts/596862.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.n5ict0.asia/arts/152100.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.n5ict0.asia/arts/613651.Doc

原标题：golang kafka offset 提交策略
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.n5ict0.asia/arts/877105.Doc

原标题：golang yaml 解析配置加载实操
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.n5ict0.asia/arts/938860.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.n5ict0.asia/arts/537705.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.n5ict0.asia/arts/273057.Doc

原标题：golang yaml 解析配置加载实操
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.n5ict0.asia/arts/474066.Doc

原标题：零基础理解读写分离基础思想
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.n5ict0.asia/arts/570511.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.n5ict0.asia/arts/207872.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.n5ict0.asia/arts/714662.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.n5ict0.asia/arts/536299.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.n5ict0.asia/arts/553193.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.n5ict0.asia/arts/602966.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.n5ict0.asia/arts/751555.Doc

原标题：本地运行正常线上报错排查
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.n5ict0.asia/arts/229299.Doc

原标题：golang mysql exists in 性能对比
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.n5ict0.asia/arts/204004.Doc

?
