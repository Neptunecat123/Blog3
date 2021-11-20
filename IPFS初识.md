# IPFS 初识

星际文件系统，InterPlanetary File System，即IPSF。

IPFS是一个旨在创建持久且分布式存储和共享文件的网络传输协议。基于以下技术：

* 分布式哈希表 DHT(Distributed Hash Table)
* 内容寻址 Content Based Addressing
* 默克尔对象关联 Object Merkle DAG
* 点对点 Peer-to-Peer
* 基于全球化命名空间 IPNS

当前的互联网协议HTTP的特点是中心化，响应式。拥有中心化的弊端和在高峰期响应延迟低峰期资源闲置的问题。

我当前的粗浅理解，IPNS相当于是BitTorrent，资源在各个用户机器上，自己获取的情况下，也提供给附近的用户就近访问。当资源变更的时候，比如blog修改了，这种情况引入git的版本控制方法解决。相当于用户的请求是带着内容和版本的。

IPFS可以解决HTTP的中心化这个问题，但带来的新问题是如果所有种子节点都下线，则全网无资源的情况。第一个方法是引入了Filecion激励，第二个方法是提供主动分发资源机制。


