最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计定时任务分布式锁防重复执行
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.ogntmfh.asia/blog/0534391.sHtMl

原标题：golang 系统设计消息队列解耦削峰
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.ogntmfh.asia/blog/1620791.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.ogntmfh.asia/blog/1799308.sHtMl

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.ogntmfh.asia/blog/9076938.sHtMl

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.ogntmfh.asia/blog/7033339.sHtMl

原标题：golang redis pipeline 批量操作
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.ogntmfh.asia/blog/5783996.sHtMl

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.ogntmfh.asia/blog/6668193.sHtMl

原标题：Architecture：对象存储接入业务整体架构
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.ogntmfh.asia/blog/6468280.sHtMl

原标题：golang 系统设计限流熔断降级组合使用
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.ogntmfh.asia/blog/8073673.sHtMl

原标题：Dockerfile 编写容器打包实战
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.ogntmfh.asia/blog/8657868.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.ogntmfh.asia/blog/3952002.sHtMl

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.ogntmfh.asia/blog/4777579.sHtMl

原标题：CLI 工具进度条交互效果开发
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.ogntmfh.asia/blog/5481233.sHtMl

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.ogntmfh.asia/blog/9713566.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.ogntmfh.asia/blog/8057232.sHtMl

原标题：git stash 代码暂存切换分支
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.ogntmfh.asia/blog/2468082.sHtMl

原标题：正则表达式文本处理实战案例
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.ogntmfh.asia/blog/7714898.sHtMl

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.ogntmfh.asia/blog/9845460.sHtMl

原标题：golang 系统设计大表加索引线上执行方案
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.ogntmfh.asia/blog/7149000.sHtMl

原标题：Security：开源项目安全审计简易检查清单
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.ogntmfh.asia/blog/2958243.sHtMl

原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://book.ogntmfh.asia/blog/4047232.sHtMl

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.ogntmfh.asia/blog/7705934.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://book.ogntmfh.asia/blog/0438860.sHtMl

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.ogntmfh.asia/blog/2495992.sHtMl

原标题：零基础理解版本控制核心概念与工作流
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.ogntmfh.asia/blog/8567126.sHtMl

原标题：golang mysql 联合索引最左匹配
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://book.ogntmfh.asia/blog/1334917.sHtMl

原标题：Performance：大事务拆分，减少锁持有时间
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.ogntmfh.asia/blog/8385623.sHtMl

原标题：golang csv 读写批量数据处理
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.ogntmfh.asia/blog/6335188.sHtMl

原标题：golang mysql 字符集排序规则设置
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.ogntmfh.asia/blog/6714949.sHtMl

原标题：macOS 脚本执行权限开启
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.ogntmfh.asia/blog/6294897.sHtMl

原标题：开发生产环境资源路径统一
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.ogntmfh.asia/blog/1622626.sHtMl

原标题：golang 数据库批量更新性能优化
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.ogntmfh.asia/blog/5755727.sHtMl

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.ogntmfh.asia/blog/1651109.sHtMl

原标题：项目实践：消息队列消息确认机制业务实践
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.ogntmfh.asia/blog/3307107.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.ogntmfh.asia/blog/4216152.sHtMl

原标题：数值类型溢出错乱问题修复
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.ogntmfh.asia/blog/2054256.sHtMl

原标题：开发记录：跨域中间件完整配置与边界处理
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.ogntmfh.asia/blog/0654137.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.ogntmfh.asia/blog/5220411.sHtMl

原标题：项目实践：Docker多环境镜像构建策略实践
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.ogntmfh.asia/blog/3919001.sHtMl

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.ogntmfh.asia/blog/4543527.sHtMl


二、踩坑排错｜Troubleshooting
原标题：方案对比：同步调用vs异步消息业务选型
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.ogntmfh.asia/blog/5377642.sHtMl

原标题：短信服务封装失败自动重试
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.ogntmfh.asia/blog/5496240.sHtMl

原标题：golang 系统设计分表字段选择路由规则设计
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.ogntmfh.asia/blog/0194292.sHtMl

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.ogntmfh.asia/blog/5487100.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.ogntmfh.asia/blog/2455072.sHtMl

原标题：TCP 心跳检测清理僵死连接
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.ogntmfh.asia/blog/1476963.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.ogntmfh.asia/blog/3965045.sHtMl

原标题：Git 误提交撤销回退实操教程
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.ogntmfh.asia/blog/8861896.sHtMl

原标题：序列化版本不一致解析失败
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.ogntmfh.asia/blog/5023311.sHtMl

原标题：golang dockerfile 多阶段构建详解
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.ogntmfh.asia/blog/6840698.sHtMl

原标题：golang 静态文件服务搭建教程
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.ogntmfh.asia/blog/8129510.sHtMl

原标题：golang etcd 分布式锁实现原理
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://book.ogntmfh.asia/blog/9801528.sHtMl

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.ogntmfh.asia/blog/8403549.sHtMl

原标题：快速上手简单信号处理脚本编写
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.ogntmfh.asia/blog/2482873.sHtMl

原标题：从零学习简单分页逻辑实现思路
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.ogntmfh.asia/blog/2412331.sHtMl

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.ogntmfh.asia/blog/9662372.sHtMl

原标题：Docker 多阶段构建镜像瘦身
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.ogntmfh.asia/blog/1113848.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.ogntmfh.asia/blog/9916632.sHtMl

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.ogntmfh.asia/blog/3787837.sHtMl

原标题：golang 错误处理最佳实践汇总
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.ogntmfh.asia/blog/8801569.sHtMl

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.ogntmfh.asia/blog/0645683.sHtMl

原标题：多环境配置中心灵活切换方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.ogntmfh.asia/blog/3137447.sHtMl

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.ogntmfh.asia/blog/4108235.sHtMl

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.ogntmfh.asia/blog/8418771.sHtMl

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.ogntmfh.asia/blog/7517088.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.ogntmfh.asia/blog/9265216.sHtMl

原标题：安全复盘：消息队列未授权访问安全加固
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.ogntmfh.asia/blog/9302534.sHtMl

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.ogntmfh.asia/blog/7436003.sHtMl

原标题：实战项目：前端资源打包体积优化完整实操
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.ogntmfh.asia/blog/0149854.sHtMl

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.ogntmfh.asia/blog/7500087.sHtMl

原标题：方案设计：分布式分页查询架构难点处理
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.ogntmfh.asia/blog/5270004.sHtMl

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.ogntmfh.asia/blog/2376860.sHtMl

原标题：golang mongodb 聚合管道实操案例
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.ogntmfh.asia/blog/4999075.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.ogntmfh.asia/blog/2792017.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.ogntmfh.asia/blog/0466351.sHtMl

原标题：进程线程并发基础概念讲解
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.ogntmfh.asia/blog/4801624.sHtMl

原标题：golang 系统设计分库分表中间件思路
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.ogntmfh.asia/blog/5512608.sHtMl

原标题：快速入门简单签名校验实现思路
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.ogntmfh.asia/blog/5172043.sHtMl

原标题：golang es 分页深分页性能优化
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.ogntmfh.asia/blog/5534798.sHtMl

原标题：golang 系统设计数据库基准压测简单思路
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.ogntmfh.asia/blog/6858360.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计告警规则阈值设置方法论
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.ogntmfh.asia/blog/5585326.sHtMl

原标题：前端打包产物体积压缩优化
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.ogntmfh.asia/blog/8668035.sHtMl

原标题：线上接口超时故障排查思路
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.ogntmfh.asia/blog/9328631.sHtMl

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.ogntmfh.asia/blog/5382636.sHtMl

原标题：golang 信号捕获程序退出处理
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.ogntmfh.asia/blog/8332737.sHtMl

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.ogntmfh.asia/blog/2778375.sHtMl

原标题：任务执行锁防止并发重复调度
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.ogntmfh.asia/blog/6298651.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.ogntmfh.asia/blog/8718474.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.ogntmfh.asia/blog/3185739.sHtMl

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://book.ogntmfh.asia/blog/2169758.sHtMl

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.ogntmfh.asia/blog/8368971.sHtMl

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.ogntmfh.asia/blog/2114945.sHtMl

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.ogntmfh.asia/blog/4930890.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.ogntmfh.asia/blog/9867096.sHtMl

原标题：Hands‑on：简易反向代理中间件实现
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.ogntmfh.asia/blog/2494689.sHtMl

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://book.ogntmfh.asia/blog/6384096.sHtMl

原标题：golang prometheus 告警规则编写
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.ogntmfh.asia/blog/4986829.sHtMl

原标题：SDK 版本兼容线上崩溃修复
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.ogntmfh.asia/blog/9257755.sHtMl

原标题：实战：容器内执行调试排错完整实操流程
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.ogntmfh.asia/blog/0582990.sHtMl

原标题：AI实践：大模型生成测试用例实践与校验
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.ogntmfh.asia/blog/6253687.sHtMl

原标题：golang 系统设计缓存优化落地实操指南
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.ogntmfh.asia/blog/1286383.sHtMl

原标题：golang redis 限流几种实现方案
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.ogntmfh.asia/blog/0494042.sHtMl

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.ogntmfh.asia/blog/0808172.sHtMl

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.ogntmfh.asia/blog/3538702.sHtMl

原标题：线上接口超时故障排查思路
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.ogntmfh.asia/blog/4245435.sHtMl

原标题：golang kafka 消费者偏移量管理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://book.ogntmfh.asia/blog/1346605.sHtMl

原标题：开发环境变量配置全平台教程
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.ogntmfh.asia/blog/3195941.sHtMl

原标题：golang http 服务性能优化调参
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.ogntmfh.asia/blog/4543746.sHtMl

原标题：golang 文件上传下载接口开发
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.ogntmfh.asia/blog/5275795.sHtMl

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.ogntmfh.asia/blog/2286597.sHtMl

原标题：实战项目：实现分布式任务调度最小原型
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.ogntmfh.asia/blog/7593699.sHtMl

原标题：JWT 令牌过期异常处理
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://book.ogntmfh.asia/blog/9977942.sHtMl

原标题：从零搭建简单的健康检查接口示例
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.ogntmfh.asia/blog/4018008.sHtMl

原标题：golang redis pipeline 原子性说明
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.ogntmfh.asia/blog/0409299.sHtMl

原标题：golang 系统设计本地缓存与分布式缓存
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.ogntmfh.asia/blog/7506311.sHtMl

原标题：跨平台 uniapp 多端开发实操
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.ogntmfh.asia/blog/7503608.sHtMl

原标题：实践：接口参数自动校验业务落地实践
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.ogntmfh.asia/blog/7299126.sHtMl

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.ogntmfh.asia/blog/2921804.sHtMl

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.ogntmfh.asia/blog/1325388.sHtMl

原标题：项目实践：消息队列消息确认机制业务实践
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.ogntmfh.asia/blog/4327832.sHtMl

四、架构设计｜Architecture
原标题：实战项目：CLI批量文件处理工具开发全过程
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.ogntmfh.asia/blog/4669231.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.ogntmfh.asia/blog/2425769.sHtMl

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.ogntmfh.asia/blog/4487981.sHtMl

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://book.ogntmfh.asia/blog/8121813.sHtMl

原标题：golang redis 过期 key 监听业务
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.ogntmfh.asia/blog/6418359.sHtMl

原标题：开发记录：容器日志标准输出采集实践方案
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.ogntmfh.asia/blog/5542092.sHtMl

原标题：正则表达式优化 CPU 占满问题
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://book.ogntmfh.asia/blog/8386134.sHtMl

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.ogntmfh.asia/blog/2058151.sHtMl

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://book.ogntmfh.asia/blog/8681980.sHtMl

原标题：多版本开发环境共存配置
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.ogntmfh.asia/blog/4550455.sHtMl

原标题：安全复盘：Redis未授权访问漏洞防护
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.ogntmfh.asia/blog/3584015.sHtMl

原标题：golang k8s service 服务暴露几种类型
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.ogntmfh.asia/blog/9641354.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://book.ogntmfh.asia/blog/3383087.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://book.ogntmfh.asia/blog/6270753.sHtMl

原标题：golang redis 网络超时参数调优
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.ogntmfh.asia/blog/4830145.sHtMl

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.ogntmfh.asia/blog/8905084.sHtMl

原标题：golang lru 缓存淘汰算法编写
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.ogntmfh.asia/blog/9736321.sHtMl

原标题：批量操作分批处理防止 OOM
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.ogntmfh.asia/blog/8882095.sHtMl

?
