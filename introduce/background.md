### 背景
------

消息队列，一般我们会简称它为MQ(Message Queue)，目前在越来越多的业务场景中被使用，例如日志收集、异步处理、服务解耦等。在业务架构中引入消息队列，我们必然要对消息队列的高可用有一定的要求，那么除了业务逻辑的实现以外，业务方必然还要关注消息队列的可靠性，包括消息丢失、消息重复、消息失败重试等机制，其实这些逻辑一般都与业务逻辑关系不大，但是却需要花费很大的精力在上面。pan致力于解决业务方在消息生产时所遇到的一系列问题，让业务方专注于业务代码的实现，有关消息队列的一切问题都交给pan。