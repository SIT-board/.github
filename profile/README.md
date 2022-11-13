# SIT-board

SIT-board 是一个开源的协作式共享白板，同时也可以当作方便的离线白板来使用。

组织中目前有三个仓库，分别如下：

[SIT-board](https://github.com/SIT-board/SIT-board) : 主要放一些项目整体架构文档， [issues](https://github.com/SIT-board/SIT-board/issues) 区进行需求方案的讨论(deprecation)，现在我们可以在 [discussions](https://github.com/SIT-board/SIT-board/discussions) 讨论。

[board_front](https://github.com/SIT-board/board_front) : 项目的客户端代码，该项目 90% 以上的代码均集中在客户端实现。

[board_backend](https://github.com/SIT-board/board_backend) : 项目的服务端代码，由于项目架构设计之初希望大部分功能尽可能在客户端实现，使客户端实现直接的分布式通信，服务器不过多参与其过程。故目前服务器的作用仅仅作为图床与附件服务器使用。
