最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计全局异常处理器实现
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://wiki.m2lh57.asia/arts/233626.Doc

原标题：golang 系统设计分布式配置中心思路
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.m2lh57.asia/arts/412941.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.m2lh57.asia/arts/953103.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/106746.Doc

原标题：项目语义化版本号规范管理
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.m2lh57.asia/arts/714430.Doc

原标题：API 接口调试与异常处理实战
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.m2lh57.asia/arts/166918.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.m2lh57.asia/arts/752683.Doc

原标题：接口请求重试容错机制实现
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.m2lh57.asia/arts/467379.Doc

原标题：动态定时任务业务调度实现
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.m2lh57.asia/arts/677363.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.m2lh57.asia/arts/899522.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.m2lh57.asia/arts/278582.Doc

原标题：请求重试组件退避策略实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.m2lh57.asia/arts/353558.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.m2lh57.asia/arts/219273.Doc

原标题：程序信号中断退出处理逻辑
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.m2lh57.asia/arts/833377.Doc

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.m2lh57.asia/arts/844615.Doc

原标题：端口占用释放资源重启服务
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://wiki.m2lh57.asia/arts/181301.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://wiki.m2lh57.asia/arts/692858.Doc

原标题：Git 误删提交代码恢复找回
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.m2lh57.asia/arts/045540.Doc

原标题：golang 重试退避机制代码实现
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.m2lh57.asia/arts/260431.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.m2lh57.asia/arts/612093.Doc

原标题：golang 单例模式实现几种方式
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.m2lh57.asia/arts/725189.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/310324.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.m2lh57.asia/arts/427023.Doc

原标题：golang prometheus histogram 指标
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.m2lh57.asia/arts/596794.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.m2lh57.asia/arts/408020.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.m2lh57.asia/arts/962257.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.m2lh57.asia/arts/574942.Doc

原标题：从零搭建本地数据库开发环境
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.m2lh57.asia/arts/480624.Doc

原标题：请求工具封装统一异常处理
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.m2lh57.asia/arts/726748.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.m2lh57.asia/arts/675169.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.m2lh57.asia/arts/606600.Doc

原标题：文件读写与异常捕获代码示例
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.m2lh57.asia/arts/566696.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.m2lh57.asia/arts/791555.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/180370.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.m2lh57.asia/arts/083218.Doc

原标题：rebase 操作防止代码丢失
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.m2lh57.asia/arts/242527.Doc

原标题：前端组件库按需加载性能优化
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.m2lh57.asia/arts/159854.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.m2lh57.asia/arts/483875.Doc

原标题：golang 系统设计 webhook 回调接口设计要点
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.m2lh57.asia/arts/582782.Doc

原标题：Git commit 钩子提交规范校验
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.m2lh57.asia/arts/949872.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.m2lh57.asia/arts/593634.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.m2lh57.asia/arts/426569.Doc

原标题：跨域偶现失败配置修复
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.m2lh57.asia/arts/571984.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.m2lh57.asia/arts/075532.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.m2lh57.asia/arts/218730.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.m2lh57.asia/arts/793937.Doc

原标题：nodejs http 服务性能调优实战
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.m2lh57.asia/arts/081470.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.m2lh57.asia/arts/135241.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.m2lh57.asia/arts/849543.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/355354.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.m2lh57.asia/arts/154327.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.m2lh57.asia/arts/664686.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.m2lh57.asia/arts/333713.Doc

原标题：入门实践：本地简单代理服务搭建
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.m2lh57.asia/arts/196811.Doc

原标题：golang 分布式锁防死锁处理
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.m2lh57.asia/arts/903245.Doc

原标题：golang gin 框架接口开发实战
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.m2lh57.asia/arts/048131.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.m2lh57.asia/arts/745176.Doc

原标题：golang 系统设计网关 websocket 转发配置要点
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/000604.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.m2lh57.asia/arts/759565.Doc

原标题：任务执行锁防止并发重复调度
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.m2lh57.asia/arts/613917.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.m2lh57.asia/arts/084925.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/843231.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.m2lh57.asia/arts/507354.Doc

原标题：golang es 聚合统计查询实现
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.m2lh57.asia/arts/236654.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.m2lh57.asia/arts/297758.Doc

原标题：golang redis 事务 multi exec 使用
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.m2lh57.asia/arts/618830.Doc

原标题：golang rsa 非对称加密签名验签
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.m2lh57.asia/arts/313288.Doc

原标题：golang websocket 消息广播实现
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.m2lh57.asia/arts/501190.Doc

原标题：golang 系统设计接口不兼容平滑迁移方案
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.m2lh57.asia/arts/152980.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.m2lh57.asia/arts/453031.Doc

原标题：golang ip 限流黑名单实现方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/675485.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.m2lh57.asia/arts/895500.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.m2lh57.asia/arts/934262.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.m2lh57.asia/arts/498244.Doc

原标题：golang mysql json 字段查询使用
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.m2lh57.asia/arts/999370.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.m2lh57.asia/arts/197368.Doc

原标题：webpack chunk 分包策略详解
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.m2lh57.asia/arts/999713.Doc

原标题：golang 布隆过滤器实现去重
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.m2lh57.asia/arts/933743.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.m2lh57.asia/arts/677786.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.m2lh57.asia/arts/699604.Doc

三、实战开发｜Practice
原标题：golang 优雅处理系统信号 SIGINT
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.m2lh57.asia/arts/612084.Doc

原标题：golang redis zset 排行榜业务实现
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.m2lh57.asia/arts/695444.Doc

原标题：异步异常捕获避免进程崩溃
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.m2lh57.asia/arts/318826.Doc

原标题：golang 告警推送钉钉机器人实现
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.m2lh57.asia/arts/600610.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.m2lh57.asia/arts/428843.Doc

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.m2lh57.asia/arts/994104.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.m2lh57.asia/arts/104799.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.m2lh57.asia/arts/459393.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.m2lh57.asia/arts/034721.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.m2lh57.asia/arts/207744.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/843707.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.m2lh57.asia/arts/042460.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/382024.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.m2lh57.asia/arts/751167.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/657785.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.m2lh57.asia/arts/174956.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.m2lh57.asia/arts/379577.Doc

原标题：golang 静态文件服务搭建教程
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.m2lh57.asia/arts/093311.Doc

原标题：golang 系统设计防爬虫简单策略
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://wiki.m2lh57.asia/arts/310314.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.m2lh57.asia/arts/352893.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.m2lh57.asia/arts/507546.Doc

原标题：ServiceWorker 缓存页面更新清理
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.m2lh57.asia/arts/721559.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://wiki.m2lh57.asia/arts/410088.Doc

原标题：golang 系统设计灰度发布实现思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.m2lh57.asia/arts/615671.Doc

原标题：布隆过滤器误判问题修正
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.m2lh57.asia/arts/728574.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.m2lh57.asia/arts/453300.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.m2lh57.asia/arts/926312.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.m2lh57.asia/arts/799547.Doc

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.m2lh57.asia/arts/367370.Doc

原标题：golang k8s job 一次性任务执行
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.m2lh57.asia/arts/504256.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.m2lh57.asia/arts/616391.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.m2lh57.asia/arts/393862.Doc

原标题：安全实践：备份文件访问权限安全管控
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.m2lh57.asia/arts/144605.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.m2lh57.asia/arts/785213.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.m2lh57.asia/arts/885485.Doc

原标题：golang 定时任务 cron 使用指南
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.m2lh57.asia/arts/850184.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.m2lh57.asia/arts/769036.Doc

原标题：golang 系统设计大表结构变更不停机方案
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.m2lh57.asia/arts/242106.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.m2lh57.asia/arts/890926.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.m2lh57.asia/arts/317292.Doc

四、架构设计｜Architecture
原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.m2lh57.asia/arts/696957.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.m2lh57.asia/arts/120140.Doc

原标题：新手参与开源社区贡献指南
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://wiki.m2lh57.asia/arts/990552.Doc

原标题：webpack chunk 分包策略详解
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.m2lh57.asia/arts/385562.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.m2lh57.asia/arts/822121.Doc

原标题：业务接口幂等完整落地案例
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.m2lh57.asia/arts/053985.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.m2lh57.asia/arts/659218.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.m2lh57.asia/arts/934221.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.m2lh57.asia/arts/160377.Doc

原标题：开发环境变量配置全平台教程
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.m2lh57.asia/arts/719882.Doc

原标题：golang 工具函数库封装思路
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.m2lh57.asia/arts/235882.Doc

原标题：golang 数据库连接泄露排查
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.m2lh57.asia/arts/863523.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.m2lh57.asia/arts/934051.Doc

原标题：golang 系统设计 mq 消息积压解决方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.m2lh57.asia/arts/504694.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.m2lh57.asia/arts/278039.Doc

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.m2lh57.asia/arts/120936.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.m2lh57.asia/arts/194667.Doc

原标题：静态站点自动部署发布方案
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.m2lh57.asia/arts/647983.Doc

?
