---
layout: home
---


<center>
    <h1>黄鹏</h1>
    <div>
        <span>
            <img src="../../image/assets/phone-solid.svg" width="18px">
            <a href="tel:18037650338">18037650338</a>
        </span>
      .
        <span>
            <img src="../../image/assets/envelope-solid.svg" width="18px">
            <a href="mailto:892645423@qq.com">892645423@qq.com</a>
        </span>
      .
        <span>
            <img src="../../image/assets/github-brands.svg" width="18px">
            <a href="https://github.com/viakiba">GitHub</a>
        </span>
      . 
        <span>
            <img src="../../image/assets/rss-solid.svg" width="18px">
            <a href="https://blog.viakiba.cn/">Blog</a>
        </span>
    </div>
    <div>
        <span>
          男，94年
        </span>
        ·
        <span>
          期望薪资：面议
        </span>
        ·
        <span>
          工作经验：7 年
        </span>
        ·
        <span>
          求职意向：后端研发
        </span>
    </div>
</center>

## <img src="../../image/assets/graduation-cap-solid.svg" width="22px"> 教育经历

- 本科 河南科技大学 物联网工程专业(计算机系) 2013.9~2017.6

## <img src="../../image/assets/briefcase-solid.svg" width="22px"> 工作经历

- Topjoy攸乐·Ace，后端研发(Java)，2022.11~2023.11
- 点点互动·Persona，后端研发(Golang)，2021.11~2022.11
- 字节跳动·Ohayoo，后端研发(Java)，2020.12~2021.11
- 开心网·开瑞工作室，后端研发(Java)，2019.11.~2020.12
- 雷森科技·研发部，后端研发(Java)，2018.4~2019.11
- 北京龙马游戏·研发部，后端研发(Java)，2017.7~2018.4

## <img src="../../image/assets/tools-solid.svg" width="22px"> 技能清单

- 前后参与 MMO, SLG, Roguelike 类型的游戏的服务器开发工作.
- 拥有从0到1的完整设计与构建游戏服务器框架的能力与经验.
- 擅长 Golang / Java / Kotlin(协程) , 了解 Python, Shell 等脚本语言.
- 精通网络 IO 框架 Mina/Netty, 热更技术, 常见的RPC框架例如 GRPC.
- 熟知 Mysql, MongoDB, Redis 的使用与调优.
- 熟悉 Spring(SpringBoot), Eureka, Feign, Ribbon, Zuul, Hystrix, MyBatis 等框架.
- 具备 Linux 常规的维护及运维的经验.

## <img src="../../image/assets/project-diagram-solid.svg" width="22px"> 项目经历

- **Topjoy·Empires Calling (手游, SLG, 试运营)**
    * 开发时间两年以上，50 人左右的项目规模，后端 4 人。
    * 采用 Java 与 自有框架 进行功能实现与开发，以及 游戏周边工具 相关开发.
    * 大小王战，世界行军，攻击方式 ，支付，礼包，订阅，排行，运营活动等开发工作。
    * 世界PVE，调整新增血量拆除实时减少的功能，使得玩家更加直观的感受到血量变化以及战力差距。
    

- **点点互动·Mafia Esper (手游, 卡牌/动作, 未上线)[Youtube实机视频](https://www.youtube.com/watch?v=IZ2gpIIh2n0)**
    * 开发时间一年以上，40 人左右的项目规模，后端 3 人。
    * 主力开发，采用 Go 与[自有框架](https://github.com/sandwich-go)进行架构设计与具体实现.
    * 主要有: 登录服务, 网关服务, 逻辑服务, 共斗(匹配), CDK/支付, 帧同步服务.
    * 数据以 Mysql 分库分表存储，采用 dbproxy 透明查询，实现游戏的不分服.
    * 登录服务器整合透明网关，实现逻辑服务器上玩家分布的负载均衡.
    * 负责设计与实现了帧同步 (KCP) 服务，并应用到共斗(多人PVE)玩法.
    * 服务器压测与服务器性能问题查找与优化.
    * 负责制定基于CPU,内存，关键错误数的服务器稳定性的预警保障机制.
    
- **字节·不休传说 (手游, 卡牌, 已上线)**

    * 服务器主程，独立负责后端研发.
    * 采用 SpringBoot + MongoDB 从0到1完整构建基于 http 的后端底层架构与功能实现.
    * 设计与构建游戏服务的基础架构，例如通信，事件，调度，配置，持久化等.
    * 开发高效的导/读表工具，支持 java, lua, json 格式的导出，并支持插件化的新增支持.
  
- **字节·狗头大作战 (手游, 卡牌, 已上线)**    
  
    * 服务器主程，独立负责后端研发.
    * 采用 kotlin(协程化) + Vertx + MongoDB 构建完全异步协程的 http 服务,20万在线时CPU (4*8c16g)平均占用 45%,平均响应低于200ms.
    * 对于含有多个动态条件复杂抽卡需求，设计了简洁且可扩展的掉落框架并与常规奖励相统一.

- **开心网·三国群英传 (手游/微信游戏, SLG, 已上线)**

    * 三国SLG手游，包含PVE,PVP,卡牌养成，装备养成,技能养成，国战，跨服组队等玩法.
    * 负责服务端游戏模块及GM系统的设计与技术实现以及部署相关脚本的维护与实现.
    * 使用 Mina 进行网络层通信, Hibernate 做数据持久化框架, Mysql 进行数据存储.
    * 热更新机制，保证代码可以进行热修复, 内置 Groovy 引擎，进行数据修复.
    * 消息混淆校验实现,微信公众号(三国群英传-争霸)礼包服务.
  
- **雷森·NFC可信服务平台** 

    * 为华为, 联想, TicWatch等客户的交通卡(北京，上海，深圳，杭州等)及银行卡装入智能设备提供技术实现.
    * 技术基于 SpringCloud 技术生态，使用 SpringBoot 和 Mybatis 并集成 Eureka 服务发现，使用feign进行服务间调用以及redis缓存.

- **龙马·天书奇谈(页游)**
  
  * 天书奇谈是人人游戏历史较长的flash页游，入职后不久，由我来整体接手并负责，在此期间，主要为游戏添加了 二级保护密码，外挂级别梯度调控（避免服务器负载过大），以及游戏活动 乾坤画匣，使者来朝，中元节，国庆节等活动.并完成日常bug的修复工作.并负责游戏GM后台的日常维护（servlet/jsp）,例如奖品发放，异常用户维护，服务器停服起服等.

- **龙马·猫游记(手游)**

  * 养成类即时战斗游戏, 参与游戏的任务模块与活动模块的研发工作.