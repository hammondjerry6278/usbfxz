最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/160322.Doc

原标题：端口占用访问失败排查方案
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/101119.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.b2hisu.asia/arts/275810.Doc

原标题：Hands‑on：简易图片压缩处理服务demo
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/617685.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.b2hisu.asia/arts/330976.Doc

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/193417.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/082652.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/744096.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.b2hisu.asia/arts/015087.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.b2hisu.asia/arts/904618.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.b2hisu.asia/arts/186540.Doc

原标题：golang prometheus histogram 指标
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.b2hisu.asia/arts/590355.Doc

原标题：golang http 请求重试封装工具
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.b2hisu.asia/arts/325515.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/660021.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.b2hisu.asia/arts/149322.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/583959.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.b2hisu.asia/arts/719464.Doc

原标题：golang 系统设计延迟队列业务实现
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.b2hisu.asia/arts/330903.Doc

原标题：新手教程：Git撤销错误提交的几种常用方式
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/523025.Doc

原标题：golang 系统设计异步化改造业务流程思路
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.b2hisu.asia/arts/296732.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/823584.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.b2hisu.asia/arts/036410.Doc

原标题：多操作系统开发兼容处理
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/668650.Doc

原标题：数据库连接池参数调优
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.b2hisu.asia/arts/841720.Doc

原标题：golang 系统信号信号量处理
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.b2hisu.asia/arts/464656.Doc

原标题：全局异常处理器接口返回统一
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.b2hisu.asia/arts/488673.Doc

原标题：golang ci 流水线环境变量管理方案
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/849607.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.b2hisu.asia/arts/164158.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.b2hisu.asia/arts/823516.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.b2hisu.asia/arts/189110.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.b2hisu.asia/arts/812153.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.b2hisu.asia/arts/889496.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.b2hisu.asia/arts/418336.Doc

原标题：golang goroutine 协程基础实操
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.b2hisu.asia/arts/419079.Doc

原标题：golang toml 配置文件解析教程
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://wiki.b2hisu.asia/arts/637306.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/828342.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.b2hisu.asia/arts/288240.Doc

原标题：项目构建脚本编译打包解析
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.b2hisu.asia/arts/040388.Doc

原标题：简易网关请求路由过滤模拟
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.b2hisu.asia/arts/270518.Doc

原标题：golang kafka 消息顺序性保证方案
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/014664.Doc


二、踩坑排错｜Troubleshooting
原标题：Hands‑on：简易消息推送服务开发实践
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.b2hisu.asia/arts/310989.Doc

原标题：golang docker compose 本地开发最佳实践
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.b2hisu.asia/arts/695197.Doc

原标题：git stash 代码暂存切换分支
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/642851.Doc

原标题：限流规则误拦截正常请求修复
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.b2hisu.asia/arts/894473.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://wiki.b2hisu.asia/arts/045260.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.b2hisu.asia/arts/977702.Doc

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.b2hisu.asia/arts/418309.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/522712.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.b2hisu.asia/arts/522814.Doc

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.b2hisu.asia/arts/563607.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.b2hisu.asia/arts/129892.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/417275.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/866598.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/156776.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/476451.Doc

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.b2hisu.asia/arts/969142.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/661665.Doc

原标题：重复提交幂等防护再次讲解
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.b2hisu.asia/arts/487736.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.b2hisu.asia/arts/612992.Doc

原标题：golang 系统设计分布式事务几种方案
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.b2hisu.asia/arts/504610.Doc

原标题：请求重试组件退避策略实现
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.b2hisu.asia/arts/672492.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.b2hisu.asia/arts/915003.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.b2hisu.asia/arts/450996.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.b2hisu.asia/arts/019334.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.b2hisu.asia/arts/942954.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.b2hisu.asia/arts/312731.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.b2hisu.asia/arts/238221.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.b2hisu.asia/arts/073142.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.b2hisu.asia/arts/931367.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.b2hisu.asia/arts/826716.Doc

原标题：golang kafka 生产者参数调优
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/444697.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/110949.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.b2hisu.asia/arts/884543.Doc

原标题：golang md5 sha 加密工具实现
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.b2hisu.asia/arts/856713.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/785446.Doc

原标题：内存广播本地进程消息通知
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.b2hisu.asia/arts/030821.Doc

原标题：golang html 模板渲染简单示例
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.b2hisu.asia/arts/106241.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.b2hisu.asia/arts/316469.Doc

原标题：模拟登录鉴权权限判断示例
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/857825.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/206369.Doc

三、实战开发｜Practice
原标题：golang etcd watch 监听配置变更
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/829170.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://wiki.b2hisu.asia/arts/935468.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.b2hisu.asia/arts/385443.Doc

原标题：从零搭建简单Mock接口服务
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.b2hisu.asia/arts/127002.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.b2hisu.asia/arts/301383.Doc

原标题：游标分页大数据查询性能提升
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.b2hisu.asia/arts/101386.Doc

原标题：golang kafka 消费者偏移量管理
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.b2hisu.asia/arts/126193.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.b2hisu.asia/arts/904802.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.b2hisu.asia/arts/647180.Doc

原标题：数据库主从延迟业务兼容处理
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.b2hisu.asia/arts/315861.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.b2hisu.asia/arts/123389.Doc

原标题：死信队列处理消息阻塞业务
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.b2hisu.asia/arts/048665.Doc

原标题：git rebase 整理提交历史实操
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.b2hisu.asia/arts/412705.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.b2hisu.asia/arts/741374.Doc

原标题：调优方案：Docker容器内核参数性能调优
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.b2hisu.asia/arts/000958.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.b2hisu.asia/arts/742472.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.b2hisu.asia/arts/633476.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.b2hisu.asia/arts/556459.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.b2hisu.asia/arts/889404.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/563175.Doc

原标题：实践：前后端分离项目登录状态保持完整方案
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.b2hisu.asia/arts/133210.Doc

原标题：快速上手搭建简易内网测试服务
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.b2hisu.asia/arts/220255.Doc

原标题：git rebase 整理提交历史实操
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.b2hisu.asia/arts/984061.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.b2hisu.asia/arts/997719.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.b2hisu.asia/arts/590038.Doc

原标题：golang 配置文件多环境加载
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.b2hisu.asia/arts/726294.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.b2hisu.asia/arts/002922.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.b2hisu.asia/arts/715987.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.b2hisu.asia/arts/426003.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/378476.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.b2hisu.asia/arts/168819.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://wiki.b2hisu.asia/arts/040352.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.b2hisu.asia/arts/642070.Doc

原标题：golang csv 读写批量数据处理
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.b2hisu.asia/arts/885815.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.b2hisu.asia/arts/774485.Doc

原标题：Nginx 反向代理路由配置实战
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.b2hisu.asia/arts/299692.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.b2hisu.asia/arts/851102.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/733756.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/670694.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.b2hisu.asia/arts/668687.Doc

四、架构设计｜Architecture
原标题：golang 系统设计大表结构变更不停机方案
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.b2hisu.asia/arts/095420.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.b2hisu.asia/arts/509549.Doc

原标题：Architecture：配置中心架构，动态配置设计思路
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.b2hisu.asia/arts/013553.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.b2hisu.asia/arts/191604.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.b2hisu.asia/arts/082736.Doc

原标题：包管理器依赖冲突解决方案
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://wiki.b2hisu.asia/arts/569525.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.b2hisu.asia/arts/720953.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.b2hisu.asia/arts/900611.Doc

原标题：Performance：批量导入数据性能优化实践
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.b2hisu.asia/arts/218660.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.b2hisu.asia/arts/277514.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.b2hisu.asia/arts/436140.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://wiki.b2hisu.asia/arts/557170.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.b2hisu.asia/arts/853557.Doc

原标题：HTTPS 证书过期更新操作
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.b2hisu.asia/arts/265548.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.b2hisu.asia/arts/241305.Doc

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.b2hisu.asia/arts/803299.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.b2hisu.asia/arts/678422.Doc

原标题：golang redis zset 排行榜业务实现
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.b2hisu.asia/arts/151589.Doc

?
