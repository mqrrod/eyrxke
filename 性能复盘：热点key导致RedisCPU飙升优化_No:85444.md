最新前沿技术资讯

一、入门教程｜Getting Started
原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3104509.sHtML

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9007035.sHtML

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1257373.sHtML

原标题：项目实践：本地模拟多节点分布式系统实践
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3567136.sHtML

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4391052.sHtML

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4873266.sHtML

原标题：时间同步修复令牌提前过期
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2085277.sHtML

原标题：golang 系统设计 commit 提交规范约定
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2608927.sHtML

原标题：入门实践：本地简单代理服务搭建
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8085799.sHtML

原标题：golang 系统设计错误码体系完整设计
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9609683.sHtML

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0562498.sHtML

原标题：设计思考：系统容量评估架构前期估算思路
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0314883.sHtML

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6618317.sHtML

原标题：golang 系统设计消息队列解耦削峰
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8299876.sHtML

原标题：前端大文件分片上传完整方案
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6723065.sHtML

原标题：入门实践：实现简单文件读写功能
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4522978.sHtML

原标题：golang 项目 docker compose 本地调试
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1943310.sHtML

原标题：文件分片上传断点续传功能
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5332603.sHtML

原标题：golang 系统设计缓存优化落地实操指南
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6083329.sHtML

原标题：开源实践：开源项目如何写好PullRequest
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3720875.sHtML

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1999414.sHtML

原标题：golang 分布式锁 redis 实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9780947.sHtML

原标题：golang k8s liveness readiness 探针
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7955184.sHtML

原标题：golang 系统设计网关 websocket 转发配置要点
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6085303.sHtML

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4622147.sHtML

原标题：Hands‑on：简易布隆过滤器实现与测试验证
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3758353.sHtML

原标题：Practice：模拟热点key，验证缓存防护策略
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7562953.sHtML

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7453613.sHtML

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8622411.sHtML

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2902496.sHtML

原标题：部署实践：容器时区统一配置解决方案
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2065648.sHtML

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9493587.sHtML

原标题：项目实践：多环境配置管理组件设计与实现
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0490834.sHtML

原标题：golang 系统设计滑动窗口限流代码示例
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9322649.sHtML

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0927158.sHtML

原标题：golang 系统设计异步化改造业务流程思路
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1631280.sHtML

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8650826.sHtML

原标题：golang es 查询语句 DSL 实操
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1016232.sHtML

原标题：优化实践：分页查询性能优化解决offset问题
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2132465.sHtML

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4396241.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang mysql 存储过程简单使用
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1513467.sHtML

原标题：分布式 ID 生成器高并发实现
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0927924.sHtML

原标题：golang 系统设计定时任务执行超时中断防护
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8389371.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4490581.sHtML

原标题：golang 开发环境快速搭建指南
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1642147.sHtML

原标题：golang 系统设计结构化日志字段规范约定
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5816164.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7826540.sHtML

原标题：前端静态缓存更新生效处理
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3513216.sHtML

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0827594.sHtML

原标题：golang prometheus histogram 指标
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9488429.sHtML

原标题：实践：前后端分离项目登录状态保持完整方案
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4024068.sHtML

原标题：全量回归测试提升代码质量
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6788975.sHtML

原标题：Architecture：服务注册发现架构原理与选型
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2315885.sHtML

原标题：前端虚拟列表大数据渲染优化
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5633359.sHtML

原标题：golang k8s rbac 权限控制配置示例
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1263646.sHtML

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6285358.sHtML

原标题：Practice：实现接口签名、验签完整示例代码
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4051849.sHtML

原标题：配置外部化线上部署防错误
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2162975.sHtML

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9369175.sHtML

原标题：快速入门ORM，实现简单数据库增删改查
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4944136.sHtML

原标题：API 大版本不兼容平滑迁移
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7181135.sHtML

原标题：golang 数据库连接泄露排查
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2365357.sHtML

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9307054.sHtML

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7217989.sHtML

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9233799.sHtML

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4645857.sHtML

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8759059.sHtML

原标题：vue pinia 状态管理实战教程
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3749414.sHtML

原标题：调优方案：CDN优化静态资源访问延迟
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9861975.sHtML

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7094503.sHtML

原标题：实战项目：WSL开发环境完整配置实操
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5234644.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0414384.sHtML

原标题：开发记录：分布式锁超时业务安全处理实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0147626.sHtML

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6698617.sHtML

原标题：接口压测定位系统性能瓶颈
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1535074.sHtML

原标题：golang 大文件读取内存优化
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6401276.sHtML

原标题：新手向：开源项目fork与同步上游代码
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7535370.sHtML

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2084221.sHtML

原标题：Performance：避免大报文，减少内存占用优化
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3532451.sHtML

原标题：实战：WebSocket断线重连完整业务处理实践
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8528162.sHtML

三、实战开发｜Practice
原标题：golang redis 大 key 识别处理方案
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9805651.sHtML

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8359914.sHtML

原标题：nestjs 拦截器过滤器管道实战
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7174645.sHtML

原标题：nestjs 全局返回格式统一处理
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7567666.sHtML

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3566865.sHtML

原标题：接口请求重试容错机制实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1240249.sHtML

原标题：日志敏感信息脱敏泄露防护
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9022682.sHtML

原标题：golang github actions 发布 release 包
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8166689.sHtML

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1519575.sHtML

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3435210.sHtML

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6302087.sHtML

原标题：golang 链路追踪简易实现方案
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5022519.sHtML

原标题：API 接口调试与异常处理实战
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4554108.sHtML

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2084234.sHtML

原标题：golang mysql 索引失效常见场景
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8316618.sHtML

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2207462.sHtML

原标题：Security：Web常见安全漏洞原理与修复清单
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8988870.sHtML

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5287236.sHtML

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3879851.sHtML

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1244662.sHtML

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3189532.sHtML

原标题：golang docker 镜像构建最佳实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8249243.sHtML

原标题：CI/CD 流水线自动构建部署落地
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7362325.sHtML

原标题：分布式 ID 全局唯一生成方案
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1074063.sHtML

原标题：golang 系统设计缓存优化落地实操指南
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8148059.sHtML

原标题：golang 布隆过滤器实现去重
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8183735.sHtML

原标题：SourceMap 生成线上报错定位
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5628165.sHtML

原标题：nodejs 集群模式多核利用实现
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6104677.sHtML

原标题：前后端交互跨域问题完整处理
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7798200.sHtML

原标题：golang 系统设计内存复用 sync.pool 使用
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8809536.sHtML

原标题：golang 系统设计配置敏感信息加密存储
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8922899.sHtML

原标题：nestjs 权限守卫鉴权实现方案
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0196971.sHtML

原标题：调优方案：Web服务内核socket参数调优
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3034503.sHtML

原标题：golang ci 流水线制品仓库上传下载
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0811022.sHtML

原标题：快速入门消息队列基础概念模型
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2911793.sHtML

原标题：golang kafka offset 提交策略
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0100681.sHtML

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6094937.sHtML

原标题：MySQL 慢查询索引优化实战
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：www.blog.lnbbx.cn/Article/details/5634011.sHtML

原标题：集成测试业务流程编写示例
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2391388.sHtML

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4203715.sHtML

四、架构设计｜Architecture
原标题：golang mysql 事务回滚异常处理
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1875868.sHtML

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4103979.sHtML

原标题：golang websocket 消息广播实现
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2022578.sHtML

原标题：css 动画性能优化 GPU 加速
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2777944.sHtML

原标题：CDN 缓存刷新获取最新静态资源
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0288659.sHtML

原标题：golang 系统设计代码评审高效沟通原则思路
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0732154.sHtML

原标题：golang 系统设计混沌测试简单场景模拟实现
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：www.blog.lnbbx.cn/Article/details/3222680.sHtML

原标题：部署实践：服务器时间同步chrony配置
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1611003.sHtML

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：www.blog.lnbbx.cn/Article/details/1568576.sHtML

原标题：golang prometheus histogram 指标
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：www.blog.lnbbx.cn/Article/details/6801506.sHtML

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：www.blog.lnbbx.cn/Article/details/2794066.sHtML

原标题：排错：前端sourcemap错误线上无法定位报错
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8777192.sHtML

原标题：golang 系统设计会话共享多实例部署
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：www.blog.lnbbx.cn/Article/details/9017374.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4580508.sHtML

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：www.blog.lnbbx.cn/Article/details/8227088.sHtML

原标题：golang k8s ingress 路由域名转发
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：www.blog.lnbbx.cn/Article/details/0400217.sHtML

原标题：golang 系统设计网关 websocket 转发配置要点
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：www.blog.lnbbx.cn/Article/details/7589793.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：www.blog.lnbbx.cn/Article/details/4175463.sHtML

?
