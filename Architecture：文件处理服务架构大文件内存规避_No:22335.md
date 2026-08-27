最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.eaxlah.asia/blog/1259853.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.eaxlah.asia/blog/9761073.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.eaxlah.asia/blog/3266769.sHtMl

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://book.eaxlah.asia/blog/1663525.sHtMl

原标题：实践：数据库备份脚本自动化编写实践
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.eaxlah.asia/blog/0253561.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.eaxlah.asia/blog/5088911.sHtMl

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.eaxlah.asia/blog/2286977.sHtMl

原标题：前端水印防信息泄露实现
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.eaxlah.asia/blog/3227341.sHtMl

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.eaxlah.asia/blog/4584389.sHtMl

原标题：灰度发布策略服务平滑升级
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.eaxlah.asia/blog/8281061.sHtMl

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.eaxlah.asia/blog/0458666.sHtMl

原标题：程序日志分级输出规范实践
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.eaxlah.asia/blog/5550637.sHtMl

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.eaxlah.asia/blog/1559019.sHtMl

原标题：nodejs 中间件模式原理剖析
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.eaxlah.asia/blog/3434628.sHtMl

原标题：axios 二次封装请求拦截处理
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://book.eaxlah.asia/blog/6207115.sHtMl

原标题：文件批量导入导出功能实现
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.eaxlah.asia/blog/6360612.sHtMl

原标题：Spring 事务传播机制配置生效
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.eaxlah.asia/blog/2322132.sHtMl

原标题：Hands‑on：简易邮件发送服务封装实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.eaxlah.asia/blog/9750376.sHtMl

原标题：新手教程：本地项目初始化gitignore配置
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.eaxlah.asia/blog/0538316.sHtMl

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.eaxlah.asia/blog/3164368.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.eaxlah.asia/blog/5866516.sHtMl

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.eaxlah.asia/blog/7586725.sHtMl

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.eaxlah.asia/blog/7497507.sHtMl

原标题：从零编写简易 CLI 命令行工具
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.eaxlah.asia/blog/8608360.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.eaxlah.asia/blog/7549773.sHtMl

原标题：复盘总结：技术选型对比文档模板实践
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.eaxlah.asia/blog/7988265.sHtMl

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://book.eaxlah.asia/blog/6217338.sHtMl

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://book.eaxlah.asia/blog/0132733.sHtMl

原标题：AI‑Dev：利用AI快速阅读陌生开源项目源码
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.eaxlah.asia/blog/6873539.sHtMl

原标题：golang rate‑limiter 限流组件
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.eaxlah.asia/blog/9736160.sHtMl

原标题：快速入门异步编程基础模型
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.eaxlah.asia/blog/1518467.sHtMl

原标题：golang 时间时区处理避坑指南
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.eaxlah.asia/blog/5929453.sHtMl

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.eaxlah.asia/blog/8599749.sHtMl

原标题：消息消费重试次数限制防爆炸
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.eaxlah.asia/blog/4201671.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.eaxlah.asia/blog/9655565.sHtMl

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.eaxlah.asia/blog/1568868.sHtMl

原标题：golang 系统设计定时任务分布式锁
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.eaxlah.asia/blog/9795686.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.eaxlah.asia/blog/1900200.sHtMl

原标题：golang 系统设计消息消费 offset 管理策略
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.eaxlah.asia/blog/3416202.sHtMl

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.eaxlah.asia/blog/5666972.sHtMl


二、踩坑排错｜Troubleshooting
原标题：Security：密码存储哈希加盐最佳实践
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.eaxlah.asia/blog/5236346.sHtMl

原标题：golang 系统设计版本号语义化规范讲解
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.eaxlah.asia/blog/9742684.sHtMl

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.eaxlah.asia/blog/8505361.sHtMl

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://book.eaxlah.asia/blog/5346520.sHtMl

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.eaxlah.asia/blog/3962270.sHtMl

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.eaxlah.asia/blog/3453940.sHtMl

原标题：Git 误删提交代码恢复找回
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.eaxlah.asia/blog/6970709.sHtMl

原标题：简易日志收集集中管理方案
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.eaxlah.asia/blog/9972649.sHtMl

原标题：Security：反序列化漏洞风险识别与规避
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.eaxlah.asia/blog/9845194.sHtMl

原标题：golang mongodb 事务多文档使用
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.eaxlah.asia/blog/1195379.sHtMl

原标题：golang 系统设计代码安全审计简单思路
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://book.eaxlah.asia/blog/0146418.sHtMl

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.eaxlah.asia/blog/7391752.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.eaxlah.asia/blog/8692573.sHtMl

原标题：部署实践：HTTPS证书自动续期配置实践
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.eaxlah.asia/blog/0562139.sHtMl

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.eaxlah.asia/blog/3396866.sHtMl

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.eaxlah.asia/blog/5606244.sHtMl

原标题：golang 系统设计第三方接口 mock 单元测试
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.eaxlah.asia/blog/6399229.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.eaxlah.asia/blog/5680780.sHtMl

原标题：nodejs 定时任务生产环境避坑
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.eaxlah.asia/blog/2349428.sHtMl

原标题：golang consul 健康检查服务注册
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.eaxlah.asia/blog/7404408.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.eaxlah.asia/blog/1408369.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.eaxlah.asia/blog/6457131.sHtMl

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.eaxlah.asia/blog/1899949.sHtMl

原标题：golang mysql 分表自增 id 方案
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.eaxlah.asia/blog/0142647.sHtMl

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.eaxlah.asia/blog/2095261.sHtMl

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.eaxlah.asia/blog/8689027.sHtMl

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.eaxlah.asia/blog/6660245.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.eaxlah.asia/blog/9612038.sHtMl

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.eaxlah.asia/blog/4185950.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.eaxlah.asia/blog/4279342.sHtMl

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.eaxlah.asia/blog/8057151.sHtMl

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.eaxlah.asia/blog/0653314.sHtMl

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.eaxlah.asia/blog/0440206.sHtMl

原标题：编译打包产物依赖分析解读
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.eaxlah.asia/blog/5669191.sHtMl

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://book.eaxlah.asia/blog/7083542.sHtMl

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://book.eaxlah.asia/blog/9980505.sHtMl

原标题：golang dockerfile 多阶段构建详解
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.eaxlah.asia/blog/1992751.sHtMl

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.eaxlah.asia/blog/0781321.sHtMl

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.eaxlah.asia/blog/5077892.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.eaxlah.asia/blog/0047627.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://book.eaxlah.asia/blog/0169334.sHtMl

原标题：多环境配置中心灵活切换方案
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://book.eaxlah.asia/blog/8142980.sHtMl

原标题：安全实践：接口错误信息不要暴露内部细节
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.eaxlah.asia/blog/5705245.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://book.eaxlah.asia/blog/6072317.sHtMl

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.eaxlah.asia/blog/0788936.sHtMl

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.eaxlah.asia/blog/6379209.sHtMl

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.eaxlah.asia/blog/7429438.sHtMl

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.eaxlah.asia/blog/3279728.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.eaxlah.asia/blog/4131592.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.eaxlah.asia/blog/2292204.sHtMl

原标题：nodejs 信号处理优雅关闭服务
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.eaxlah.asia/blog/1822795.sHtMl

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.eaxlah.asia/blog/2907536.sHtMl

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://book.eaxlah.asia/blog/3626914.sHtMl

原标题：golang 系统设计性能优化通用思路方法论
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.eaxlah.asia/blog/3631350.sHtMl

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.eaxlah.asia/blog/7761206.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.eaxlah.asia/blog/6777107.sHtMl

原标题：Practice：实现多数据源动态切换组件实践
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.eaxlah.asia/blog/8952347.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.eaxlah.asia/blog/0564781.sHtMl

原标题：CI 持续集成自动构建流程
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.eaxlah.asia/blog/6016525.sHtMl

原标题：golang 系统设计网关 websocket 转发配置要点
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.eaxlah.asia/blog/4849232.sHtMl

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://book.eaxlah.asia/blog/8507895.sHtMl

原标题：接口幂等性防重复请求实现
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.eaxlah.asia/blog/7451413.sHtMl

原标题：异步编程 Promise 执行流程解析
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.eaxlah.asia/blog/9204019.sHtMl

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.eaxlah.asia/blog/8216380.sHtMl

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.eaxlah.asia/blog/0493789.sHtMl

原标题：前端打包产物体积压缩优化
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://book.eaxlah.asia/blog/6464548.sHtMl

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.eaxlah.asia/blog/8563177.sHtMl

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.eaxlah.asia/blog/4847861.sHtMl

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.eaxlah.asia/blog/6556784.sHtMl

原标题：golang 单元测试 table‑driven
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.eaxlah.asia/blog/1491869.sHtMl

原标题：从零搭建本地数据库开发环境
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.eaxlah.asia/blog/0641491.sHtMl

原标题：容器资源限制防止宿主机过载
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.eaxlah.asia/blog/5202630.sHtMl

原标题：开源项目本地运行排错完整清单
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.eaxlah.asia/blog/2543153.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://book.eaxlah.asia/blog/1261720.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://book.eaxlah.asia/blog/4166317.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.eaxlah.asia/blog/4270720.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.eaxlah.asia/blog/0193699.sHtMl

原标题：nodejs 跨域中间件配置细节
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.eaxlah.asia/blog/0204244.sHtMl

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.eaxlah.asia/blog/2315203.sHtMl

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.eaxlah.asia/blog/3462196.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://book.eaxlah.asia/blog/2279917.sHtMl

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://book.eaxlah.asia/blog/5338352.sHtMl

原标题：接口幂等性防重复请求实现
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.eaxlah.asia/blog/5207023.sHtMl

原标题：开源项目本地运行排错完整清单
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.eaxlah.asia/blog/6890354.sHtMl

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.eaxlah.asia/blog/8939084.sHtMl

原标题：内存溢出问题现象识别排查
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.eaxlah.asia/blog/3585286.sHtMl

原标题：golang kafka 同步异步消费对比
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.eaxlah.asia/blog/5783824.sHtMl

原标题：golang 分布式 ID 雪花算法实现
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.eaxlah.asia/blog/3613903.sHtMl

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://book.eaxlah.asia/blog/9971699.sHtMl

原标题：Practice：实现限流之后友好业务返回处理
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.eaxlah.asia/blog/1120514.sHtMl

原标题：灰度发布策略服务平滑升级
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.eaxlah.asia/blog/9786273.sHtMl

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://book.eaxlah.asia/blog/3163234.sHtMl

原标题：GC 垃圾回收优化降低 CPU 占用
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.eaxlah.asia/blog/7136677.sHtMl

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.eaxlah.asia/blog/4160719.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.eaxlah.asia/blog/6001153.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.eaxlah.asia/blog/1984389.sHtMl

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.eaxlah.asia/blog/2676917.sHtMl

原标题：nodejs http 服务性能调优实战
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.eaxlah.asia/blog/1640059.sHtMl

?
