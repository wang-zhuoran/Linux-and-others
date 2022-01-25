# tmux
## 功能
1. 分屏。
2. 允许断开Terminal连接后，继续运行进程。

## 结构
    一个tmux可以包含多个session，一个session可以包含多个window，  一个window可以包含多个pane。    
    实例：  
        tmux:  
            session 0:  
                window 0:  
                    pane 0  
                    pane 1  
                    pane 2  
                    ...  
                window 1  
                window 2  
                ...  
            session 1  
            session 2  
            ...  
## 操作

