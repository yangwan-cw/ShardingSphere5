![ShardingSphere Logo](assets/logo_v3.png)

<!-- TOC -->

- [一、ShardingSphere 是什么？](#%E4%B8%80shardingsphere-%E6%98%AF%E4%BB%80%E4%B9%88)
    - [1. 历史渊源](#1-%E5%8E%86%E5%8F%B2%E6%B8%8A%E6%BA%90)
        - [1.1. 单库单表的性能瓶颈](#11-%E5%8D%95%E5%BA%93%E5%8D%95%E8%A1%A8%E7%9A%84%E6%80%A7%E8%83%BD%E7%93%B6%E9%A2%88)
        - [1.2. 手动解决单表庞大](#12-%E6%89%8B%E5%8A%A8%E8%A7%A3%E5%86%B3%E5%8D%95%E8%A1%A8%E5%BA%9E%E5%A4%A7)
- [二、高性能数据库集群架构模式](#%E4%BA%8C%E9%AB%98%E6%80%A7%E8%83%BD%E6%95%B0%E6%8D%AE%E5%BA%93%E9%9B%86%E7%BE%A4%E6%9E%B6%E6%9E%84%E6%A8%A1%E5%BC%8F)
- [版本](#%E7%89%88%E6%9C%AC)
- [贡献者](#%E8%B4%A1%E7%8C%AE%E8%80%85)
- [仓库信息](#%E4%BB%93%E5%BA%93%E4%BF%A1%E6%81%AF)
- [贡献者](#%E8%B4%A1%E7%8C%AE%E8%80%85)

<!-- /TOC -->


# 一、ShardingSphere 是什么？
定位：数据库增强引擎，提供透明化的分布式数据库能力。

## 历史渊源

### 单库单表的性能瓶颈
> ⚠️ 问题: 当单表数据量增长到千万级甚至更大时，查询性能急剧下降（如全表扫描耗时剧增），索引效率降低，写入速度变慢。
💡 传统方案：升级硬件（如换 SSD、增加内存），但成本高且效果有限

### 手动解决单表庞大
> ⚠️ 问题: 需自行设置分片规则（如按HASH,取余）,并在代码逻辑上进行编码，导致产生连锁问题
- ​​侵入性强​​：业务代码与分片逻辑耦合，难以维护。

# 二、高性能数据库集群架构模式

1. 🔄 [读写分离](2.读写分离.md)
2. 🗂️ [数据分片](3.数据分片.md)
3. [实现方式](4.实现方式.md)
4. [环境安装](5.docker环境安装.md)
   





# 版本
> 🏷️ 5.1.1

# 贡献者

# 仓库信息
[![Forks](https://img.shields.io/github/forks/yangwan-cw/ShardingSphere5)](https://github.com/yangwan-cw/ShardingSphere5/network/members)
[![Stars](https://img.shields.io/github/stars/yangwan-cw/ShardingSphere5)](https://github.com/yangwan-cw/ShardingSphere5/stargazers)
[![Commits](https://img.shields.io/github/commit-activity/t/yangwan-cw/ShardingSphere5)](https://img.shields.io/github/commit-activity/t/yangwan-cw/ShardingSphere5)


# 贡献者
<!-- readme: collaborators,contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/yangwan-cw">
            <img src="https://avatars.githubusercontent.com/u/50450947?v=4" width="100;" alt="yangwan-cw"/>
            <br />
            <sub><b>Yangwan-cw</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: collaborators,contributors -end -->