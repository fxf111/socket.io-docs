- gitbook 见 ：https://socket.gitbook.io/docs/
- github page 见：https://veaba.github.io/socket.io-docs/


# Socket.io 文档中文翻译项目

在过去，曾多次使用到socket.io，但也仅仅是使用基础的模块。最近因为自己做了一个比较大的消息推送架构，再次使用到了socket.io，不由的感慨，这真是一个优秀的社区项目。

为了更加深入学习和使用socket.io，现在我把它的文档中文翻译下，也方便自己学习。


## 目录

* [关于本socket.io中文文档](https://github.com/veaba/socket.io-docs)
    * [socket.IO官方网站](https://socket.io/)
    * [gitbook见](https://socket.gitbook.io/docs/)
    * [github page 见](https://veaba.github.io/socket.io-docs/)
* [1 指南(Guide)]()
    * [1-1 介绍(Introduction)](guide/introduction.md)
    * [1-2 web框架(The web framework)](guide/the_web_framework.md)
    * [1-3 服务HTML(Serving HTML)](guide/serving_html.md)
    * [1-4 集成 socket.io(Integrating socket.io)](guide/integrating_socket.io.md)
    * [1-5 发送事件(Emiting events)](guide/emitting_events.md)
    * [1-6 广播(Broadcasting)](guide/broadcasting.md)
    * [1-7 作业(Homework)](guide/homework.md)
    * [1-8 获取示例(Getting this example)](guide/getting_this_example.md)

* [2  文档(Docs)]()
    * [2.1 概览]()
        * [2.1.1 啥是Socket.io](docs/overview/what_socket.io_is.md)    
        * [2.1.2 Socket.io不是什么](docs/overview/what_socket.io_is_not.md)    
        * [2.1.3 安装](docs//overview/installing.md)    
        * [2.1.4 在Node HTTP 服务中使用](docs/overview/using_with_node_http_server.md)    
        * [2.1.5 在express中使用Socket.io](docs/overview/using_with_express.md)    
        * [2.1.6 发送和接收事件](docs/overview/sending_and_receiving_events.md)    
        * [2.1.7 限制自己使用命名空间](docs/overview/restricting_yourself_to_a_namespace.md)
        * [2.1.8 发送易失性的消息](docs/overview/sending_volatile_message.md)    
        * [2.1.9 发送和获取数据(确认)](docs/overview/sending_and_getting_data_acknowledgements.md)  
        * [2.1.10 广播消息](docs/overview/broadcasting_messages.md)   
        * [2.1.111 作为跨浏览器使用websocket](docs/overview/using_it_just_as_a_cross_browser_websocket.md)     

    * [2.2 房间和命名空间]()
        * [2.2.1 命名空间](docs/rooms_and_namespaces/namespaces.md)
        * [2.2.2 房间](docs/rooms_and_namespaces/rooms.md)
        * [2.2.3 给外部发送消息](docs/rooms_and_namespaces/sending_message_from_the_outside-world.md)

    * [2.3 从0.9迁移版本 migrating_from_0.9]()
        * [2.3.1 身份验证差异](docs/migrating_from_0.9/authentication_differences.md )
        * [2.3.2 日志差异](docs/migrating_from_0.9/log_differences.md)
        * [2.3.3 快捷方式](docs/migrating_from_0.9/shorcuts.md)
        * [2.3.4 配置差异](docs/migrating_from_0.9/configuration_differences.md)
        * [2.3.5 解析器/协议差异](docs/migrating_from_0.9/parser_protocol_differences.md)

    * [2.4 多路节点使用]()
        * [2.4.1 Apache httpd配置](docs/using_multiple_nodes/apache_httpd_configuration.md)
        * [2.4.2 在节点之间传递事件](docs/using_multiple_nodes/passing_events_between_nodes.md)
        * [2.4.3 Haproxy配置](docs/using_multiple_nodes/haproxy_configuration.md)
        * [2.4.4 粘性负载均衡](docs/using_multiple_nodes/sticky_load_balancing.md)
        * [2.4.5 Nginx配置](docs/using_multiple_nodes/nginx_configuration.md)
        * [2.4.6 使用node.js集群](docs/using_multiple_nodes/using_node.js_cluster.md)

    * [2.5 日志和调试]()
        * [2.5.1 可用的调试范围](docs/logging_and_debugging/available_debugging_scopes.md)

    * [2.6 emit 备忘单](docs/emit_cheatsheet.md)

    * [2.7 内部概述]()
        * [2.7.1 内部概述引擎底层依赖关系图](docs/internals_overview_dependency_graph_under_the_hood.md)
        * [2.7.2 内部概述关系图](docs/internals_overview_dependency_graph.md)

    * [2.8 faq](docs/faq.md)   

* [3 客户端-API(Client-API)]()
    * [3.1 io]()
        * [3.1.1 io.protocpl](client-api/io/io_protocol.md)
        * [3.1.2 io([url][,optiosn])](client-api/io/io_url_options.md)
        * [3.1.3 初始化示例-带多路复用](client-api/io/initialization_examples_with_multiplexing.md)
        * [3.1.4 初始化示例-自定义路径](client-api/io/initialization_examples_with_custom_path.md)
        * [3.1.5 初始化示例-查询参数](client-api/io/initialization_examples_with_query_parameters.md)
        * [3.1.6 初始化示例-查询选项](client-api/io/initialization_examples_with_query_option.md)
        * [3.1.7 初始化示例-额外Headers](client-api/io/initialization_examples_with_extraHeaders.md)
        * [3.1.8 初始化示例-仅限websocket传输](client-api/io/initialization_examples_with_websockets_transport_only.md)
        * [3.1.9 初始化示例-自定义解析器](client-api/io/initialization_examples_with_a_custom_parser.md)
        * [3.1.11 初始化示例-自签名证书](client-api/io/initialization_examples_width_a_sele-signed_certificate.md)

    * [3.2 manager]()
        * [3.2.1 new Manager(url[,options])](client-api/manager/new_manager_url_options.md)
        * [3.2.2 manager.reconnection([value])](client-api/manager/nmanager_reconnection_value.md)
        * [3.2.3 manager.reconnectionAttempts([value])](client-api/manager/nmanager_reconnectionAttempts_value.md)
        * [3.2.4 manager.reconnectionDelay.([value])](client-api/manager/nmanager_reconnectionDelay_value.md)
        * [3.2.5 manager.reconnectionDelayMax([value])](client-api/manager/nmanager_reconnectionDelayMax_value.md)
        * [3.2.6 manager.timeout(pvalue[])](client-api/manager/nmanager_timeout_value.md)
        * [3.2.7 manager.open([callback])](client-api/manager/nmanager_open_callback.md)
        * [3.2.8 manager.connect([callback])](client-api/manager/nmanager_connect_callback.md)
        * [3.2.9 manager.socket(nsp,options)](client-api/manager/nmanager_socket_nsp_options.md)
        * [3.2.10 event:connect_error](client-api/manager/nevent_connect_error.md)
        * [3.2.11 event:connect_timeout](client-api/manager/nevent_connect_timeout.md)
        * [3.2.12 event:reconnect](client-api/manager/nevent_reconnect.md)
        * [3.2.13 event:reconnect_attempt](client-api/manager/nevent_reconnect_attempt.md)
        * [3.2.14 event:reconnecting](client-api/manager/nevent_reconnecting.md)
        * [3.2.15 event:reconnect_error](client-api/manager/nevent_reconnect_error.md)
        * [3.2.16 event:reconnect_failed](client-api/manager/nevent_reconnect_failed.md)
        * [3.2.17 event:ping](client-api/manmanagerage/nevent_ping.md)
        * [3.2.18 event:pong](client-api/manager/nevent_pong.md)

    * [3.3 socket]()
        * [3.3.1 socket.id](client-api/socket/socket_id.md)
        * [3.3.2 socket.connected](client-api/socket/socket_connected.md)
        * [3.3.3 socket.disconnected](client-api/socket/socket_disconnected.md)
        * [3.3.4 socket.open()](client-api/socket/socket_open.md)
        * [3.3.5 socket.connect()](client-api/socket/socket_connect.md)
        * [3.3.6 socket.send([...args][,ack])](client-api/socket/socket_send_args_ack.md)
        * [3.3.7 socket.emit(eventName,[...args][,ack])](client-api/socket/socket_emit_eventName_args_ack.md)
        * [3.3.8 socket.on(eventName,callback)](client-api/socket/socket_on_eventName_callback.md)
        * [3.3.9 socket.compress(value)](client-api/socket/socket_compress_value.md)
        * [3.3.10 socket.binary(value)](client-api/socket/socket_binary_value.md)
        * [3.3.11 socket.close()](client-api/socket/socket_close.md)
        * [3.3.12 socket.disconnect()](client-api/socket/socket_disconnect.md)
        * [3.3.13 event:connect](client-api/socket/event_connect.md)
        * [3.3.14 event:connect_error](client-api/socket/event_connect_error.md)
        * [3.3.15 event:connect_timeout](client-api/socket/event_connect_timeout.md)
        * [3.3.16 event:error](client-api/socket/event_error.md)
        * [3.3.17 event:disconnect](client-api/socket/event_disconnect.md)
        * [3.3.18 event:reconnect](client-api/socket/event_reconnect.md)
        * [3.3.19 event:reconnect_attempt](client-api/socket/event_reconnect_attempt.md)
        * [3.3.20 event:reconnenting](client-api/socket/event_reconnenting.md)
        * [3.3.21 event:reconnect_error](client-api/socket/event_reconnect_error.md)
        * [3.3.22 event:reconnect_failed](client-api/socket/event_reconnect_failed.md)
        * [3.3.23 event:ping](client-api/socket/event_ping.md)
        * [3.3.24 event:pong](client-api/socket/event_pong.md)

* [4 服务端-API(Server-API)]()

    * [4.1 server]()
        * [4.1.1 HTTP服务选项 new_server_httpserver_options](server-api/server/new_server_httpserver_options.md)
        * [4.1.2 服务器端口选项 new_server_port_options](server-api/server/new_server_port_options.md)
        * [4.1.3 服务器选项 new_server_options](server-api/server/new_server_options.md)
        * [4.1.4 服务器sockets server_sockets](server-api/server/server_sockets.md)
        * [4.1.5 服务器serverClient值 server_serverClient_value](server-api/server/server_serverClient_value.md)
        * [4.1.6 服务器路径值 server_path_value](server-api/server/server_path_value.md)
        * [4.1.7 服务器适配器值 server_adapter_value](server-api/server/server_adapter_value.md)
        * [4.1.8 服务器源值 server_origins_value](server-api/server/server_origins_value.md)
        * [4.1.9 服务器源函数 server_origins_fn](server-api/server/server_origins_fn.md)
        * [4.1.10 服务器附加HTTP服务选项 server_attach_httpServer_options](server-api/server/server_attach_httpServer_options.md)
        * [4.1.11 服务器附加端口选项 server_attach_port_options](server-api/server/server_attach_port_options.md)
        * [4.1.12 服务器监听HTTP服务选项 server_listen_httpServer_options](server-api/server/server_listen_httpServer_options.md)
        * [4.1.13 服务器监听端口选项 server_listent_port_options](server-api/server/server_listent_port_options.md)
        * [4.1.14 服务器绑定引擎 server_bind_engine](server-api/server/server_bind_engine.md)
        * [4.1.15 服务器连接socket server_onconnection_socket](server-api/server/server_onconnection_socket.md)
        * [4.1.16 服务器命名空间(nsp) server_of_nsp](server-api/server/server_of_nsp.md)
        * [4.1.17 服务器关闭回调 server_close_callback](server-api/server/server_close_callback.md)
        * [4.1.18 服务器引擎生成socket ID server_engine_generateid](server-api/server/server_engine_generateid.md)

    * [4.2 命名空间(namespace)]()
        * [4.2.1 命名空间 namespace](server-api/namespace/namespace.md)
        * [4.2.2 命名空间名称 namespace_name](server-api/namespace/namespace_name.md)
        * [4.2.3 命名空间连接 namespace_connected](server-api/namespace/namespace_connected.md)
        * [4.2.4 命名空间适配器 namespace_adapter](server-api/namespace/namespace_adapter.md)
        * [4.2.5 命名空间到房间 namespace_to_room](server-api/namespace/namespace_to_room.md)
        * [4.2.6 命名空间在房间 namespace_in_room](server-api/namespace/namespace_in_room.md)
        * [4.2.7 命名空间发送事件参数 namespace_emit_eventname_args](server-api/namespace/namespace_emit_eventname_args.md)
        * [4.2.8 命名空间客户端回调 namespace_clients_callback](server-api/namespace/namespace_clients_callback.md)
        * [4.2.9 命名空间中间件函数 namespace_use_fn](server-api/namespace/namespace_use_fn.md)
        * [4.2.10 连接事件 event_connect](server-api/namespace/event_connect.md)
        * [4.2.11 事件连接 event_connection](server-api/namespace/event_connection.md)
        * [4.2.12 可见性标志位 flag_volatile](server-api/namespace/flag_volatile.md)
        * [4.2.13 二进制标志位 flag_binary](server-api/namespace/flag_binary.md)
        * [4.2.14 本地标记位 flag_local](server-api/namespace/flag_local.md)
        
    * [4.3 socket]()
        * [4.3.1 socket_id](server-api/socket/socket_id.md)
        * [4.3.2 socket_rooms](server-api/socket/socket_rooms.md)
        * [4.3.3 socket_client](server-api/socket/socket_client.md)
        * [4.3.4 socket_conn](server-api/socket/socket_conn.md)
        * [4.3.5 socket_request](server-api/socket/socket_request.md)
        * [4.3.6 socket_handshake](server-api/socket/socket_handshake.md)
        * [4.3.7 socket_use_fn](server-api/socket/socket_use_fn.md)
        * [4.3.8 socket_send_args_ack](server-api/socket/socket_send_args_ack.md)
        * [4.3.9 socket_emit_eventName_args_ack](server-api/socket/socket_emit_evenName_args_ack.md)
        * [4.3.10 socket_on_eventName_callback](server-api/socket/socket_on_eventName_callback.md)
        * [4.3.11 socket_once_eventName_listener](server-api/socket/socket_once_eventName_listener.md)
        * [4.3.12 socket_removelistener_eventName_listener](server-api/socket/socket_removelistener_eventName_listener.md)
        * [4.3.13 socket_removeAllListeners_eventName](server-api/socket/socket_removeAllListeners_eventName.md)
        * [4.3.14 socket_eventNames](server-api/socket/socket_eventNames.md)
        * [4.3.15 socket_join_room_callback](server-api/socket/socket_join_room_callback.md)
        * [4.3.16 socket_join_rooms_callback](server-api/socket/socket_join_rooms_callback.md)
        * [4.3.17 socket_leave_room_callback](server-api/socket/socket_leave_room_callback.md)
        * [4.3.18 socket_to_room](server-api/socket/socket_to_room.md)
        * [4.3.19 socket_in_room](server-api/socket/socket_in_room.md)
        * [4.3.20 socket_compress_value](server-api/socket/socket_compress_value.md)
        * [4.3.21 socket_disconnect_close](server-api/socket/socket_disconnect_close.md)
        * [4.3.22 flag_broadcast](server-api/socket/flag_broadcast.md)
        * [4.3.23 flag_volatile](server-api/socket/flag_volatile.md)
        * [4.3.24 flag_binary](server-api/socket/flag_binary.md)
        * [4.3.25 event_disconnect](server-api/socket/event_disconnect.md)
        * [4.3.26 event_error](server-api/socket/event_error.md)
        * [4.3.27 event_disconnecting](server-api/socket/event_disconnecting.md)
    * [4.4 client]()
        * [4.4.1 client](server-api/client/client.md)
        * [4.4.2 client_conn](server-api/client/client_conn.md)
        * [4.4.3 client_request](server-api/client/client_request.md)



## 术语

### 术语转换
|错误|校正|
|---|----|
|`客户机`|客户端|
|`套接字`|socket|
|`插座`|socket|
|`发射`|发送|
|`分析器`|解析器|
|`underlying`|底层|
|`激发`|触发|
|||

### 英文翻译
- `traditionally 传统，一直以来`
- `involves 涉及`
- `polling 投票、轮询`
- `goal 目标，得分，母的`
- `populate 填充、补完`
- `confufing 混乱 混淆`
- `entire 整个`
- `placed 放置`
- `instead 相反的`
- `refactor 重构`
- `composed 组成`
- `exposes 暴露` 
- `several 一些` 
- `behind 背后`
- `prevents 放置` 
- `broadcasting 广播` 
- `the rest 其余`
- `in order to 为了`
- `except 除了`
- `certain 某些`
- `in the case 在这种情况下`
- `for the sake of simplicity 为了简单起见`
- `capture  捕获`
- `total 全部`
- `amounts 量、等于、合计`
- `directly z直接地 `
- `presses 按下`
- `typing 打字`
- `functionality 功能`
- `improvements 改进`
- `enables 可以，使能够`
- `real-time 实时`
- `bidirectional 双向的` 
- `event-based 基于事件`
- `communication 通信、沟通`
- `between 之间`
- `consists 包括`
- `which can  也可以`
- `Multiplexing 多路复用`
- `established 建立`
- `presence 存在`
- `load balancers 负载均衡器`
- `firewall 防火墙`
- `purpose 目的`
- `antivirus 防病毒`
- `relies 依赖`
- `polling 轮询 `
- `goals 目标`
- `For this purpose 为此`
- `Unless 除非`
- `instructed 得到指示`
- `otherwise 否则`
- `heartbeat 心跳`
- `mechanism 机智`
- `implemented 实现、实施，贯彻，使生效`
- `allowing 允许`
- `anymore 不在`
- `functionality 功能`
- `acheieved  实现、达到`
- `handshake 握手`
- `serializable 可序列化的`
- `structures 结构`
- `separation 分离`
- `concerns 关注`
- `per 每`
- `underlying connection 底层连接`
- `arbitrary 任意`
- `reaching 到达`
- `given 给定、特定、指定`
- `useful 有用`
- `standalone 独立`
- `served 服务`
- `implementations 实现方式`
- `several 几个`
- `maintained 维护、保持`
- `besides 此外，除了`
- `restricting 限制`
- `reception 接待、接受`
- `volatile 不稳定的`
- `certain 某些 `
- `essentially  本质上`
- `assigning 分配`
- `minimize 减少`
- `identified `
- `short form 简写`


_________________________________________

by @veaba

2019年3月13日13:39:15

