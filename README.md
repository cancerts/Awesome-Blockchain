# 区块链技术图谱
[![知识共享协议（CC协议）](https://img.shields.io/badge/License-Creative%20Commons-DC3D24.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)
[![GitHub watchers](https://img.shields.io/github/watchers/cancerts/awesome-blockchain.svg?style=flat&label=Watch)](https://github.com/cancerts/awesome-blockchain/watchers)
[![GitHub stars](https://img.shields.io/github/stars/cancerts/awesome-blockchain.svg?style=flat&label=Star)](https://github.com/cancerts/awesome-blockchain/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/cancerts/awesome-blockchain.svg?style=flat&label=Fork)](https://github.com/cancerts/awesome-blockchain/fork)

## 区块链基础知识

### 区块链基本概念
* [区块](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#区块)
* [账本](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#账本)
* [共识](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#共识)
* [去中心化](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#去中心化)
  * [DAPP](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#DAPP)
* [智能合约](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#智能合约)
  * [smart-contract](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#smart-contract)
  * [chaincode](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#chaincode)
* [挖矿](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#挖矿)
  * [矿池](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#矿池)
  * [旷工](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#旷工)
  * [矿机](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#矿机)
* [token（代币）](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#token（代币）)
  * [ICO](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#ICO)
* [钱包](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#钱包)
  * [核心客户端](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#核心客户端)
  * [轻量钱包](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#轻量钱包)
* [交易所](https://github.com/cancerts/Awesome-Blockchain/blob/master/README.md#交易所)

### 密码学
* 哈希算法
  * 哈希函数简介
  * 哈希函数性质
    * 抗碰撞
    * 信息隐藏
    * 蜜汁难解
  * SHA-1
    * MD5
  * SAH-2
    * SHA-224
    * SAH-256
    * SHA-384
  * SHA-3
    * Keccak
    * BLAKE
    * GROSTL
    * JH
    * SKEIN
* Merkle 树
  * 哈希指针
  * Merkle 哈希树
* 对称加密

* 非对称加密
    * 公钥加密-私钥解密
    * 私钥加密-公钥解密
* 签名机制
  * 数字证书
  * 数字签名
    * ECDSA
    * 环签名
    * 盲签名
    * 群签名
    * 零知识证明
* PKI 体系

### 分布式共识
* 核心问题
  * 分布式共识
    * 一致性问题
    * 可靠性指标
  * 拜占庭问题
  
* 共识系统基本定理
  * FLP定理
  * CAP定理
  * ACID原则
  
* 共识协议
  * VR 
  * Paxos
  * Raft
  
* 共识算法
  * POW
  * POS
  * DPOS
  * PBFT
  * 

### p2p网络
* p2p简介
* 协议
  * TCP/IP
  * UDP
* 数据结构与算法
  * 非机构化p2p系统
  * 结构化p2p系统
    * 分布式哈希表（DHT）
    * DHT 协议
    * 哈希算法
    * 路由算法
    

-------------------------
## 区块链代表

# 比特币

* 链接 
  * 官网
  * 白皮书
    * 英文
    * 中文

* 比特币介绍
  * 货币的起源
  * 比特币的社会价值
  * 比特币的发行机制
  * 比特币交易所
  * 比特币浏览器
  * 比特币社区

* 运行原理
  * 比特币的账号系统
    * UTXO 账户模型
    * 公钥-私钥-地址
    * Base58 账户地址编码
    * 签名
    * 荣耀地址
    * 支付到公钥哈希(p2pKH)
    * 支付到脚本哈希（p2SH）
    * 客户端
    
 * 记账原理
   * 交易
   * 比特币网络
   * 挖矿
     * 旷池
     * 旷工
     * 矿机
     * 算力
     * 哈希函数
     * POW
   * 区块结构  
   * 打包区块
   * 扩容与软硬分叉之殇
   * 秘密的保护--匿名性和隐私性
   
* 比特币脚本

* 比特币改进协议

* 比特币安全
  
* 开发实战
  * 环境准备
  * 实例

-------------------
# 以太坊
  
* 链接 
  * 官网
    * 中文
    * 英文
  * 白皮书
    * 英文
    * 中文
    
* 以太坊介绍
  * 什么是以太坊
  * 以太坊基础
  * 以太坊虚拟机（EVM）
  * solidity介绍
  
* 以太坊账户
  * 合约账户
  * 外部账户
  * 密钥和地址
  * RLP编码
  * Merkle Patricia树
  
* 打包原理
  * 交易
    * 燃料（gas）
  * 消息
  * 以太坊网络
  * 挖矿
    * 共识算法
    * 算力
    * 激励
  * 区块结构
  * 打包区块
  * 数据库
  * 以太坊分叉
* 智能合约
  * 智能合约介绍
  * 编写智能合约
    * remix介绍
    * 本地编写
  * 合约编译和测试
  * 部署智能合约
  * 实例
* 去中心化应用（DAPP）
  * 前端简介
  * web3介绍
  * 实例
* 代币（token）
  * 代币介绍
  * EIPS
    * ERC20
  * 实例
* 预言机（Oracles）
* 开发工具、框架和库
  * 框架
    * Truffle
    * Embark
    * OpenZeppelin
    * zeppelin_os
  * 工具
    * Dapp
    * Seth
    * Hevm
  * 库
    * web3.js
    * web3.py
    * web3j
    * EthereumJS
    * Etherjar
    * Nethereum
    * ethers.js
 --------------------   
# 超级账本
* 链接 
  * 官网
  * 白皮书
    * 英文
    * 中文
* 超级账本介绍
  * 什么是超级账本
  * 超级账本基础
  * Linux简介
  * 超级账本中国工作组
  * golang简介
  
* Fabric
  * 官网
    * 中文
    * 英文
    
  * 框架
    * 网络层
      * Gossip
      * 节点
    * 核心层
      * 共识机制
        * solo
        * kafka
        * zookeeper
      * 权限权利
        * 成员管理
        * 证书管理
    * 业务层
      * 通道
      * 链码
        * 链码简介
        * 编写链码
        * 部署链码
        * 实例
          * 0.6
          * 1.0
      * 交易
      * 区块
      * 账本
      * 实例
  
  * 组件
    * CA
    * MSP 
    * Client
    * Orderer
    * Committer
    * Endorser
  * docker
    * docker 介绍
    * docker从入门到实战
    
* Sawtooth
  * 官网
  * 简介
  
* Iroha
  * 官网
  * 简介
  
* Burrow
  * 官网
  * 简介
  
* Indy
  * 官网
  * 简介
  
* Cello
  * 官网
  * 简介
  
* Composer
  * 官网
  * 简介
  
* Explorer
  * 官网
  * 简介
  
* Quilt
  * 官网
  * 简介
  
* Caliper
  * 官网
  * 简介

# 区块
# 账本
# 共识
# 去中心化
## DAPP
# 智能合约
## smart-contract
## chaincode
# 挖矿
## 矿池
## 旷工
## 矿机
# token（代币）
## ICO
# 钱包
## 核心客户端
## 轻量钱包
# 交易所

# 密码学
# 哈希算法
## 哈希函数简介
## 哈希函数性质
### 抗碰撞
### 信息隐藏
### 蜜汁难解
## SHA-1
### MD5
## SAH-2
### SHA-224
### SAH-256
    * SHA-384
  * SHA-3
    * Keccak
    * BLAKE
    * GROSTL
    * JH
    * SKEIN
* Merkle 树
  * 哈希指针
  * Merkle 哈希树
* 对称加密

* 非对称加密
    * 公钥加密-私钥解密
    * 私钥加密-公钥解密
* 签名机制
  * 数字证书
  * 数字签名
    * ECDSA
    * 环签名
    * 盲签名
    * 群签名
    * 零知识证明
* PKI 体系

### 分布式共识
* 核心问题
  * 分布式共识
    * 一致性问题
    * 可靠性指标
  * 拜占庭问题
  
* 共识系统基本定理
  * FLP定理
  * CAP定理
  * ACID原则
  
* 共识协议
  * VR 
  * Paxos
  * Raft
  
* 共识算法
  * POW
  * POS
  * DPOS
  * PBFT
  * 

### p2p网络
* p2p简介
* 协议
  * TCP/IP
  * UDP
* 数据结构与算法
  * 非机构化p2p系统
  * 结构化p2p系统
    * 分布式哈希表（DHT）
    * DHT 协议
    * 哈希算法
    * 路由算法
    

-------------------------
## 区块链代表

# 比特币

* 链接 
  * 官网
  * 白皮书
    * 英文
    * 中文

* 比特币介绍
  * 货币的起源
  * 比特币的社会价值
  * 比特币的发行机制
  * 比特币交易所
  * 比特币浏览器
  * 比特币社区

* 运行原理
  * 比特币的账号系统
    * UTXO 账户模型
    * 公钥-私钥-地址
    * Base58 账户地址编码
    * 签名
    * 荣耀地址
    * 支付到公钥哈希(p2pKH)
    * 支付到脚本哈希（p2SH）
    * 客户端
    
 * 记账原理
   * 交易
   * 比特币网络
   * 挖矿
     * 旷池
     * 旷工
     * 矿机
     * 算力
     * 哈希函数
     * POW
   * 区块结构  
   * 打包区块
   * 扩容与软硬分叉之殇
   * 秘密的保护--匿名性和隐私性
   
* 比特币脚本

* 比特币改进协议

* 比特币安全
  
* 开发实战
  * 环境准备
  * 实例

-------------------
# 以太坊
  
* 链接 
  * 官网
    * 中文
    * 英文
  * 白皮书
    * 英文
    * 中文
    
* 以太坊介绍
  * 什么是以太坊
  * 以太坊基础
  * 以太坊虚拟机（EVM）
  * solidity介绍
  
* 以太坊账户
  * 合约账户
  * 外部账户
  * 密钥和地址
  * RLP编码
  * Merkle Patricia树
  
* 打包原理
  * 交易
    * 燃料（gas）
  * 消息
  * 以太坊网络
  * 挖矿
    * 共识算法
    * 算力
    * 激励
  * 区块结构
  * 打包区块
  * 数据库
  * 以太坊分叉
* 智能合约
  * 智能合约介绍
  * 编写智能合约
    * remix介绍
    * 本地编写
  * 合约编译和测试
  * 部署智能合约
  * 实例
* 去中心化应用（DAPP）
  * 前端简介
  * web3介绍
  * 实例
* 代币（token）
  * 代币介绍
  * EIPS
    * ERC20
  * 实例
* 预言机（Oracles）
* 开发工具、框架和库
  * 框架
    * Truffle
    * Embark
    * OpenZeppelin
    * zeppelin_os
  * 工具
    * Dapp
    * Seth
    * Hevm
  * 库
    * web3.js
    * web3.py
    * web3j
    * EthereumJS
    * Etherjar
    * Nethereum
    * ethers.js
 --------------------   
# 超级账本
* 链接 
  * 官网
  * 白皮书
    * 英文
    * 中文
* 超级账本介绍
  * 什么是超级账本
  * 超级账本基础
  * Linux简介
  * 超级账本中国工作组
  * golang简介
  
* Fabric
  * 官网
    * 中文
    * 英文
    
  * 框架
    * 网络层
      * Gossip
      * 节点
    * 核心层
      * 共识机制
        * solo
        * kafka
        * zookeeper
      * 权限权利
        * 成员管理
        * 证书管理
    * 业务层
      * 通道
      * 链码
        * 链码简介
        * 编写链码
        * 部署链码
        * 实例
          * 0.6
          * 1.0
      * 交易
      * 区块
      * 账本
      * 实例
  
  * 组件
    * CA
    * MSP 
    * Client
    * Orderer
    * Committer
    * Endorser
  * docker
    * docker 介绍
    * docker从入门到实战
    
* Sawtooth
  * 官网
  * 简介
  
* Iroha
  * 官网
  * 简介
  
* Burrow
  * 官网
  * 简介
  
* Indy
  * 官网
  * 简介
  
* Cello
  * 官网
  * 简介
  
* Composer
  * 官网
  * 简介
  
* Explorer
  * 官网
  * 简介
  
* Quilt
  * 官网
  * 简介
  
* Caliper
  * 官网
  * 简介
