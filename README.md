# 什么是ark宇宙
&emsp;&emsp;Ark宇宙是我个人在十多年职业生涯中，个人成果的结晶。包括：
- 个人写的一些中间件;
- 个人写的一些平台性质的服务;
- 个人沉淀总结的架构（包括应用架构/技术架构/业务架构/数据架构）方面的实践和方法论;
- 个人沉淀总结的中间件/组件的最佳实践;
- 个人沉淀撰写的软件全生命周期过程中涉及的各种规范和研发流程。
- 个人在团队管理方面的一些心得和方法论。

希望能够帮助到大家，如果有什么问题，欢迎提issue，我会尽快回复。
   
# Ark宇宙

| 序号 | 类别 | 名称 | 使用场景 | 链接 |
| :----: |:----: | :----: | :----: | :----: |
| 1 | 中间件篇 | ark服务目录框架 | 文档api和源码实时同步保持一致  | [ark-service-directory](https://github.com/javaboy863/ark-service-directory) |
| 2 | 中间件篇 | ark流程编排框架 | 流程编排框架，用于中台等业务复杂的场景 | [ark-flow-engine](https://github.com/javaboy863/ark-flow-engine) |
| 3 | 中间件篇 | ark事务补偿框架 | 基于本地消息表的事务补偿框架 | [ark-tc](https://github.com/javaboy863/ark-tc) |
| 4 | 中间件篇 | ark日志框架 |  统一日志格式输出、日志文件分级、全链路trace| [ark-log](https://github.com/javaboy863/ark-log) |
| 5 | 中间件篇 | ark-super-pom框架 |  jar依赖统一管控 | [ark-super-pom](https://github.com/javaboy863/ark-super-pom) |
| 6 | 中间件篇 | ark-httpclient框架 |  发起http请求场景 | [ark-common-httpclient](https://github.com/javaboy863/ark-common-httpclient) |
| 7 | 中间件篇 | ark数据对比框架 | 数据对比场景 | [ark-common-data-compare](https://github.com/javaboy863/ark-common-data-compare) |
| 8 | 中间件篇 | ark-rocketmq-client框架 | 业务解耦、削峰填谷 | [ark-rocketmq-client](https://github.com/javaboy863/ark-rocketmq-client.git) |
| 9 | 中间件篇 | ark-jetcache框架 | 使用本地+远程两级缓存 | [ark-jetcache](https://github.com/javaboy863/ark-jetcache.git) |
| 10 | 中间件篇 | ark-sentinel框架 | 限流降级 | [ark-sentinel](https://github.com/javaboy863/ark-sentinel.git) |
| 11 | 中间件篇 | ark分层框架1.0 | 是一种应用架构，是对整洁架构的一种实现 | [ark-layer-framework](https://github.com/javaboy863/ark-layer-framework) |
| 12 | 中间件篇 | ark测试框架 | 用于集成测试和单元测试的场景,支持自动录制和回放 | [ark-test-framework](https://github.com/javaboy863/ark-test-framework) |
| 13 | 架构篇 | ark分层框架2.0项目实践 | 基于分层框架1.0,在此基础上做了全新升级 | [ark-layer-framework 2.0实践](https://github.com/javaboy863/ark-sample-clean-code) |
| 14 | 架构篇 | ark系统稳定性方法论 | 架构稳定性方法论 | [稳定性](https://github.com/javaboy863/ark-arch/tree/main/arch-stability) |
| 15 | 架构篇 | ark整洁架构方法论 | 整洁架构方法论 | [整洁架构](https://github.com/javaboy863/ark-arch/tree/main/arch-clean-architecture) |
| 16 | 架构篇 | ark整洁代码方法论 | 整洁代码方法论 | [整洁代码](https://github.com/javaboy863/ark-arch/tree/main/arch-clean-code) |
| 17 | 架构篇 | ark测试环境稳定性治理实践 | 测试环境稳定性治理实践 | [测试环境稳定性治理](https://github.com/javaboy863/ark-best-practices/tree/main/testing-environment) |
| 18 | 架构篇 | ark DDD | DDD实践总结 | [DDD实践总结](https://github.com/javaboy863/ark-DDD) |
| 19 | 平台篇 |ark业务校验平台 | 各类业务规则校验,如1分钟未推单,订单状态异常等 | [ark-bcp](https://github.com/javaboy863/ark-bcp) |
| 20 | 平台篇 |ark监控-异常播报服务 | 生产环境异常报警通知 | [ark-monitor-bug-repoter](https://github.com/javaboy863/ark-monitor-bug-repoter) |
| 21 | 平台篇 |ark监控-全链路业务监控 | 全链路业务健康监控 | [ark-monitor-full-process-business](https://github.com/javaboy863/ark-monitor-full-process-business) |
| 22 | 平台篇 |ark dubbo摘挂流量服务 | 服务治理和摘挂流量 | [ark-dubbo-governance](https://github.com/javaboy863/ark-dubbo-governance) |
| 23 | 平台篇 |ark多版本jar管理服务 | 多版本jar管理 | [ark-multiple-jar-manager](https://github.com/javaboy863/ark-multiple-jar-manager) |
| 24 | 平台篇 |ark网关服务 | 流量网关 | [ark-gateway](https://github.com/javaboy863/ark-gateway) |
| 25 | 平台篇 |ark规则引擎平台 | 规则引擎平台 | [ark-rule-platform](https://github.com/javaboy863/ark-rule-platform) |
| 26 | 平台篇 | ark分布式ID服务 | 分布式ID，生成全局唯一ID | [ark-leaf](https://github.com/javaboy863/ark-leaf) |
| 27 | 中台篇 | ark交易中台 | 不同业态的交易场景 | [交易中台](https://github.com/javaboy863/ark-middle-end/tree/main/trading-middle-end) |
| 28 | 中台篇 | ark营销中台 | 不同业态的营销场景 | [营销中台](https://github.com/javaboy863/ark-middle-end/tree/main/marketing-middle-end) |
| 29 | 中台篇 | ark商品中台 | 不同业态的商品场景 | [商品中台](https://github.com/javaboy863/ark-middle-end/tree/main/product-middle-end) |
| 30 | 最佳实践篇 | ark nacos最佳实践 | nacos使用最佳实践 | [nacos最佳实践](https://github.com/javaboy863/ark-best-practices/tree/main/nacos) |
| 31 | 最佳实践篇 | ark分布式锁实践 | 分布式锁使用最佳实践 | [分布式锁最佳实践](https://github.com/javaboy863/ark-best-practices/tree/main/distributed-lock) |
| 32 | 最佳实践篇 | ark 测试环境稳定性最佳实践 | 测试环境稳定性最佳实践 | [测试环境稳定性最佳实践](https://github.com/javaboy863/ark-best-practices/tree/main/testing-environment) |
| 33 | 团队管理篇 | ark虚线TeamLeader方法论 | 虚线TL方法论 | [虚线TL方法](https://github.com/javaboy863/ark-management/tree/main/dotted-line-team-leader) |
| 34 | 团队管理篇 | ark实线TeamLeader方法论 | 实线TL方法论 | [实线TL方法](https://github.com/javaboy863/ark-management/tree/main/solid-line-team-leader) |
| 35 | 研发流程规范篇 | ark技术评审规范 | 《技术方案评审规范》 | [技术方案评审规范](https://github.com/javaboy863/ark-standard/tree/main/grooming-system-standard) |
| 36 | 研发流程规范篇 | ark研发分支管理规范 | 《研发分支管理规范》 | [研发分支管理规范](https://github.com/javaboy863/ark-standard/tree/main/git-standrad) |
| 37 | 研发流程规范篇 | ark业务系统限流降级 | 《业务系统限流降级》 | [业务系统限流降级](https://github.com/javaboy863/ark-standard/tree/main/rate-limit-standrad) |
| 38 | 研发流程规范篇 | ark系统压测规范 | 《系统压测规范》 | [系统压测规范](https://github.com/javaboy863/ark-standard/tree/main/stress-test-standrad) |
| 39 | 研发流程规范篇 | ark业务系统梳理规范及产出标准 | 《业务系统梳理规范及产出标准》 | [业务系统梳理规范及产出标准](https://github.com/javaboy863/ark-standard/tree/main/technical-solution-standard) |
| 40 | 日常踩坑篇 | dubbo踩坑系列 | dubbo踩坑记录 | [dubbo踩坑系列](https://github.com/javaboy863/daily-problem/tree/main/dubbo) |
