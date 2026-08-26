最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 commit 提交规范约定
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.yxdzuc.asia/arts/299118.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.yxdzuc.asia/arts/484092.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.yxdzuc.asia/arts/293007.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.yxdzuc.asia/arts/136897.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.yxdzuc.asia/arts/033557.Doc

原标题：golang mysql 索引失效常见场景
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.yxdzuc.asia/arts/679325.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.yxdzuc.asia/arts/241657.Doc

原标题：golang redis hyperloglog 基数统计
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.yxdzuc.asia/arts/400437.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/724506.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.yxdzuc.asia/arts/706813.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/873016.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.yxdzuc.asia/arts/183824.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.yxdzuc.asia/arts/528725.Doc

原标题：golang gorm 批量插入性能调优
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.yxdzuc.asia/arts/432016.Doc

原标题：golang 系统设计大文件上传架构
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/685898.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/279311.Doc

原标题：nodejs 数据库连接池配置调优
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.yxdzuc.asia/arts/179607.Doc

原标题：前端图片懒加载性能优化
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.yxdzuc.asia/arts/801943.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.yxdzuc.asia/arts/932797.Doc

原标题：全局异常处理器接口返回统一
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/677832.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.yxdzuc.asia/arts/095190.Doc

原标题：WSL 文件权限访问异常修复
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.yxdzuc.asia/arts/926854.Doc

原标题：golang 简易埋点日志上报实现
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/510579.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.yxdzuc.asia/arts/228469.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.yxdzuc.asia/arts/873586.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/709832.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.yxdzuc.asia/arts/075010.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/739414.Doc

原标题：快速入门对象存储基础使用场景
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.yxdzuc.asia/arts/488124.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.yxdzuc.asia/arts/077972.Doc

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/807972.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://wiki.yxdzuc.asia/arts/169653.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/144043.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.yxdzuc.asia/arts/073832.Doc

原标题：前端错误监控上报系统搭建
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.yxdzuc.asia/arts/325459.Doc

原标题：golang mysql exists in 性能对比
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.yxdzuc.asia/arts/750192.Doc

原标题：不必要字符转义关闭业务异常
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/365130.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.yxdzuc.asia/arts/984609.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.yxdzuc.asia/arts/773228.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.yxdzuc.asia/arts/748902.Doc


二、踩坑排错｜Troubleshooting
原标题：WSL 文件权限访问异常修复
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.yxdzuc.asia/arts/332920.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.yxdzuc.asia/arts/883977.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.yxdzuc.asia/arts/769454.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.yxdzuc.asia/arts/710165.Doc

原标题：代码格式化工具团队统一风格
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.yxdzuc.asia/arts/927696.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/263553.Doc

原标题：Hands‑on：简易代理服务器开发实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/314363.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.yxdzuc.asia/arts/992460.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.yxdzuc.asia/arts/077270.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.yxdzuc.asia/arts/445659.Doc

原标题：Architecture：链路追踪架构核心组件与埋点
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.yxdzuc.asia/arts/181651.Doc

原标题：golang 单元测试 table‑driven
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.yxdzuc.asia/arts/927341.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.yxdzuc.asia/arts/668357.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.yxdzuc.asia/arts/895743.Doc

原标题：Git 混乱提交历史清理方法
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/300930.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/639027.Doc

原标题：浏览器缓存强制刷新方案
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.yxdzuc.asia/arts/380939.Doc

原标题：golang 系统设计序列化性能选型对比
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.yxdzuc.asia/arts/065372.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/452100.Doc

原标题：golang docker compose 部署 minio
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/314716.Doc

原标题：golang 系统设计采样策略降低链路存储开销
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.yxdzuc.asia/arts/707249.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.yxdzuc.asia/arts/171360.Doc

原标题：react 状态管理方案选型对比
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.yxdzuc.asia/arts/632860.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.yxdzuc.asia/arts/381223.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.yxdzuc.asia/arts/234969.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.yxdzuc.asia/arts/171772.Doc

原标题：零基础理解依赖管理与包管理器
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.yxdzuc.asia/arts/971032.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.yxdzuc.asia/arts/539815.Doc

原标题：golang grafana 监控面板简单配置
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.yxdzuc.asia/arts/439944.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.yxdzuc.asia/arts/594804.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.yxdzuc.asia/arts/511020.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.yxdzuc.asia/arts/327625.Doc

原标题：golang 系统设计分库分表中间件思路
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/627994.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.yxdzuc.asia/arts/814002.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.yxdzuc.asia/arts/666518.Doc

原标题：golang 重试退避机制代码实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.yxdzuc.asia/arts/942517.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/583578.Doc

原标题：golang 消息死信处理业务逻辑
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.yxdzuc.asia/arts/876086.Doc

原标题：分布式 ID 全局唯一生成方案
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.yxdzuc.asia/arts/475838.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.yxdzuc.asia/arts/080285.Doc

三、实战开发｜Practice
原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.yxdzuc.asia/arts/073329.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.yxdzuc.asia/arts/931942.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.yxdzuc.asia/arts/616021.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.yxdzuc.asia/arts/523040.Doc

原标题：vue pinia 状态管理实战教程
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.yxdzuc.asia/arts/284368.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/864020.Doc

原标题：本地运行正常线上报错排查
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/909883.Doc

原标题：golang 时间时区处理避坑指南
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://wiki.yxdzuc.asia/arts/303899.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.yxdzuc.asia/arts/147535.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.yxdzuc.asia/arts/844338.Doc

原标题：golang k8s service 服务暴露几种类型
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.yxdzuc.asia/arts/667926.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.yxdzuc.asia/arts/076059.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.yxdzuc.asia/arts/740726.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.yxdzuc.asia/arts/035244.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.yxdzuc.asia/arts/035381.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.yxdzuc.asia/arts/006685.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.yxdzuc.asia/arts/280552.Doc

原标题：golang 系统设计 websocket 协议原理梳理
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.yxdzuc.asia/arts/298227.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.yxdzuc.asia/arts/556737.Doc

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.yxdzuc.asia/arts/016565.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.yxdzuc.asia/arts/312573.Doc

原标题：DevOps：CI构建产物缓存复用加速编译
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.yxdzuc.asia/arts/771237.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.yxdzuc.asia/arts/403437.Doc

原标题：从零学习基础的接口请求与参数处理
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.yxdzuc.asia/arts/840612.Doc

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.yxdzuc.asia/arts/552211.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.yxdzuc.asia/arts/373867.Doc

原标题：golang 系统设计容器健康检查设计思路
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.yxdzuc.asia/arts/868681.Doc

原标题：定时任务周期调度 demo 开发
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.yxdzuc.asia/arts/749491.Doc

原标题：golang ci 流水线环境变量管理方案
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.yxdzuc.asia/arts/910123.Doc

原标题：业务幂等键设计防重复逻辑
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.yxdzuc.asia/arts/317885.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.yxdzuc.asia/arts/551807.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.yxdzuc.asia/arts/609101.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.yxdzuc.asia/arts/652520.Doc

原标题：golang redis 批量 pipeline 实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.yxdzuc.asia/arts/820804.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.yxdzuc.asia/arts/349370.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.yxdzuc.asia/arts/598626.Doc

原标题：golang 信号量控制并发数量
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/154988.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.yxdzuc.asia/arts/739300.Doc

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.yxdzuc.asia/arts/962479.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.yxdzuc.asia/arts/998342.Doc

四、架构设计｜Architecture
原标题：gitignore 文件编写过滤规则
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.yxdzuc.asia/arts/818387.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.yxdzuc.asia/arts/475676.Doc

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.yxdzuc.asia/arts/527907.Doc

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/891342.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.yxdzuc.asia/arts/884673.Doc

原标题：golang 数据库慢查询监控实现
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.yxdzuc.asia/arts/184216.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.yxdzuc.asia/arts/221190.Doc

原标题：语义化版本依赖管理防错乱
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.yxdzuc.asia/arts/711652.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.yxdzuc.asia/arts/499543.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.yxdzuc.asia/arts/144896.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.yxdzuc.asia/arts/609171.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.yxdzuc.asia/arts/223012.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.yxdzuc.asia/arts/446673.Doc

原标题：快速上手搭建简易内网测试服务
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.yxdzuc.asia/arts/651286.Doc

原标题：WebSocket 断线重连稳定优化
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.yxdzuc.asia/arts/534703.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.yxdzuc.asia/arts/031676.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.yxdzuc.asia/arts/594624.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.yxdzuc.asia/arts/850653.Doc

?
