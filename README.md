# 以太坊数据分析 - Ethereum ETL

#### 目录

0. 前言
    * 0.1 Blockchain ETL
        * 支持导出数据
        * 计划中
1. 概览
    * 1.1 导出数据
        * 表结构
    * 1.2 应用
2. 命令
3. 导出区块链数据
    * 3.1 导出最新的100个区块所有区块链数据
        * 最新的一百个区块区间以及当前时间戳
        * 导出数据并统计时间
        * 查看output目录
        * 统计csv行数
        * 查看每个csv前2行
        * 读取csv，并查看前2行
        * 数据清洗
        * 数据分析
    * 3.2 2小时内导出方案
4. 使用Google BigQuery查询区块数据（SQL）
    * 4.1 表探索
        * 区块
        * 交易
        * ERC20（代币） / ERC721（NFT）
        * 通证交易
        * 收据
        * 日志
        * 合约
        * 内部交易
    * 4.2 数据洞察
        * 余额最多的账户
        * 以太币每日总供应量
        * 两笔内部交易间最短路径
        * 最近90天挖矿最多的几个账户
        * 不同区块链交易吞吐量对比
5. 源码解读
    * 5.1 下载源码
    * 5.2 JSON RPC 请求
    * 5.3 jobs
    * 5.4 common
    * 5.5 blocks & transactions
    * 5.6 token transfers
    * 5.7 receipts & logs
    * 5.8 contracts
    * 5.9 tokens
    * 5.10 traces
6. 附：导出共识节点数据
    * 6.1 导出数据
        * 表结构
    * 6.2 命令
    * 6.3 使用BigQuery查询
        * 有哪些表
        * beacon_blocks
        * beacon_committees
        * validators

详情见[Ethereum ETL.ipynb](https://github.com/adalee2future/ethereum-analysis/blob/main/Ethereum%20ETL.ipynb)
