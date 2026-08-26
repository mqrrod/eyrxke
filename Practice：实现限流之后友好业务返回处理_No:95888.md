最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现限流之后友好业务返回处理
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.0a865u.asia/arts/265360.Doc

原标题：HTTPS 证书过期更新操作
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.0a865u.asia/arts/074411.Doc

原标题：架构复盘：慢查询治理架构层面优化手段
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.0a865u.asia/arts/699066.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.0a865u.asia/arts/537178.Doc

原标题：Git 子模块更新代码不全修复
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.0a865u.asia/arts/380713.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.0a865u.asia/arts/488810.Doc

原标题：nodejs 中间件模式原理剖析
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://wiki.0a865u.asia/arts/144385.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.0a865u.asia/arts/014603.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.0a865u.asia/arts/325110.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.0a865u.asia/arts/051888.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.0a865u.asia/arts/862205.Doc

原标题：golang redis bitmap 位图统计实现
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.0a865u.asia/arts/506146.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.0a865u.asia/arts/794503.Doc

原标题：短信服务封装失败自动重试
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.0a865u.asia/arts/506385.Doc

原标题：消息消费重试次数限制防爆炸
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.0a865u.asia/arts/037803.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.0a865u.asia/arts/055125.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.0a865u.asia/arts/167763.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.0a865u.asia/arts/543810.Doc

原标题：CI 构建缓存加速编译速度
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.0a865u.asia/arts/210357.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.0a865u.asia/arts/443453.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.0a865u.asia/arts/994342.Doc

原标题：vue pinia 状态管理实战教程
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.0a865u.asia/arts/765445.Doc

原标题：GET POST 接口请求参数处理
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.0a865u.asia/arts/898515.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://wiki.0a865u.asia/arts/798855.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.0a865u.asia/arts/756346.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.0a865u.asia/arts/311518.Doc

原标题：golang gin 框架接口开发实战
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.0a865u.asia/arts/800334.Doc

原标题：vue pinia 状态管理实战教程
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.0a865u.asia/arts/139040.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.0a865u.asia/arts/333452.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.0a865u.asia/arts/258215.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.0a865u.asia/arts/937974.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.0a865u.asia/arts/366057.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.0a865u.asia/arts/536380.Doc

原标题：golang 系统设计序列化性能选型对比
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.0a865u.asia/arts/169014.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.0a865u.asia/arts/316784.Doc

原标题：golang redis 分布式计数器开发
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.0a865u.asia/arts/126566.Doc

原标题：golang docker compose 部署 minio
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.0a865u.asia/arts/964264.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.0a865u.asia/arts/599360.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.0a865u.asia/arts/936707.Doc

原标题：golang 系统设计内存高占用排查思路
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.0a865u.asia/arts/898129.Doc


二、踩坑排错｜Troubleshooting
原标题：避坑：请求未设置read超时无限挂起连接
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.0a865u.asia/arts/183354.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.0a865u.asia/arts/495010.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.0a865u.asia/arts/920998.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.0a865u.asia/arts/139785.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.0a865u.asia/arts/076130.Doc

原标题：部署实践：Nginx高可用配置方案实践
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.0a865u.asia/arts/677762.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.0a865u.asia/arts/118493.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.0a865u.asia/arts/566067.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.0a865u.asia/arts/247762.Doc

原标题：开发记录：表单参数校验统一中间件实现
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.0a865u.asia/arts/014465.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.0a865u.asia/arts/635846.Doc

原标题：golang redis 过期 key 监听业务
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.0a865u.asia/arts/729589.Doc

原标题：超大数据集分页性能优化方案
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.0a865u.asia/arts/318269.Doc

原标题：golang websocket 服务端开发
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.0a865u.asia/arts/728659.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.0a865u.asia/arts/869368.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.0a865u.asia/arts/074084.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.0a865u.asia/arts/407491.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.0a865u.asia/arts/686673.Doc

原标题：Practice：实现请求重试组件支持退避策略
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.0a865u.asia/arts/055974.Doc

原标题：跨平台换行符统一异常修复
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.0a865u.asia/arts/909079.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.0a865u.asia/arts/009168.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.0a865u.asia/arts/457648.Doc

原标题：Git 子模块更新代码不全修复
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.0a865u.asia/arts/151244.Doc

原标题：消息消费重试次数限制防爆炸
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.0a865u.asia/arts/540007.Doc

原标题：golang 系统设计分库分表 id 全局生成策略
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.0a865u.asia/arts/462559.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.0a865u.asia/arts/071469.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.0a865u.asia/arts/575768.Doc

原标题：网关超时时间调优后端等待
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.0a865u.asia/arts/052106.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.0a865u.asia/arts/489911.Doc

原标题：golang 系统设计秒杀防超卖方案
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.0a865u.asia/arts/135309.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.0a865u.asia/arts/631266.Doc

原标题：开发测试生产多环境配置区分
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.0a865u.asia/arts/785959.Doc

原标题：golang 大文件读取内存优化
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.0a865u.asia/arts/799644.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.0a865u.asia/arts/995992.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.0a865u.asia/arts/303851.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://wiki.0a865u.asia/arts/221834.Doc

原标题：文件描述符优化进程卡死修复
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.0a865u.asia/arts/530302.Doc

原标题：业务错误码体系设计方案
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.0a865u.asia/arts/202883.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.0a865u.asia/arts/946654.Doc

原标题：任务执行锁防止并发重复调度
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.0a865u.asia/arts/566729.Doc

三、实战开发｜Practice
原标题：排错：前端缓存304异常更新不及时
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.0a865u.asia/arts/555751.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.0a865u.asia/arts/404218.Doc

原标题：golang proto 默认值坑点梳理
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.0a865u.asia/arts/717262.Doc

原标题：golang base64 编码解码实操
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.0a865u.asia/arts/200366.Doc

原标题：配置与镜像分离防止信息泄露
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.0a865u.asia/arts/549841.Doc

原标题：全平台系统环境变量配置
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.0a865u.asia/arts/060404.Doc

原标题：全量回归测试提升代码质量
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.0a865u.asia/arts/085693.Doc

原标题：代码模块化组件化拆分思路
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.0a865u.asia/arts/506998.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.0a865u.asia/arts/765530.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.0a865u.asia/arts/906898.Doc

原标题：快速入门简单签名校验实现思路
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.0a865u.asia/arts/895881.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.0a865u.asia/arts/349965.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.0a865u.asia/arts/465255.Doc

原标题：golang docker 容器资源限制设置
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.0a865u.asia/arts/903106.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.0a865u.asia/arts/125134.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.0a865u.asia/arts/868205.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://wiki.0a865u.asia/arts/330717.Doc

原标题：golang prometheus histogram 指标
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.0a865u.asia/arts/139696.Doc

原标题：零基础理解前后端简单交互流程
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.0a865u.asia/arts/018581.Doc

原标题：全局本地依赖隔离冲突规避
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.0a865u.asia/arts/895251.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.0a865u.asia/arts/133090.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.0a865u.asia/arts/237299.Doc

原标题：移动端适配 rem vw 方案对比
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.0a865u.asia/arts/617883.Doc

原标题：容器软链接文件权限修复
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.0a865u.asia/arts/197473.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.0a865u.asia/arts/607760.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.0a865u.asia/arts/286382.Doc

原标题：golang context 上下文传参讲解
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.0a865u.asia/arts/270488.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.0a865u.asia/arts/855828.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.0a865u.asia/arts/122177.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.0a865u.asia/arts/503210.Doc

原标题：golang 单元测试 table‑driven
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.0a865u.asia/arts/207339.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.0a865u.asia/arts/510304.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.0a865u.asia/arts/123607.Doc

原标题：批量数据处理脚本编写技巧
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.0a865u.asia/arts/112499.Doc

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.0a865u.asia/arts/555747.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.0a865u.asia/arts/161700.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.0a865u.asia/arts/071784.Doc

原标题：golang k8s 节点污点容忍度配置
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.0a865u.asia/arts/865089.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.0a865u.asia/arts/011219.Doc

原标题：react 状态管理方案选型对比
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.0a865u.asia/arts/053910.Doc

四、架构设计｜Architecture
原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.0a865u.asia/arts/343066.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.0a865u.asia/arts/016788.Doc

原标题：端口占用释放资源重启服务
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.0a865u.asia/arts/072193.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.0a865u.asia/arts/692988.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.0a865u.asia/arts/269716.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.0a865u.asia/arts/612563.Doc

原标题：golang 系统设计重试退避策略业务落地
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.0a865u.asia/arts/870314.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.0a865u.asia/arts/115358.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.0a865u.asia/arts/952755.Doc

原标题：golang github actions 发布 release 包
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.0a865u.asia/arts/074514.Doc

原标题：操作系统内核版本适配服务
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.0a865u.asia/arts/955898.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.0a865u.asia/arts/688533.Doc

原标题：eslint prettier 代码规范落地
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.0a865u.asia/arts/301644.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.0a865u.asia/arts/370058.Doc

原标题：快速上手搭建简易内网测试服务
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.0a865u.asia/arts/547663.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.0a865u.asia/arts/862170.Doc

原标题：Practice：简易限流器分布式版本Redis实现
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.0a865u.asia/arts/698565.Doc

原标题：golang redis 布隆过滤器安装使用
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.0a865u.asia/arts/181967.Doc

?
