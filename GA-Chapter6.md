第六章 广度优先搜索     
广度优先搜索让你能够找出两样东西之间的最短距离，   
图算法是最有用的算法  
最短路径问题 shortest-path problem   

解决最短路径问题的算法被称为广度优先搜索。   

P79  
图由节点node和边组成edge  
一个节点与众多节点直接相连，这些节点被称为邻居。  

P80  
广度优先搜索可帮助回答两类问题：   
从节点A出发，有前往节点B的路径吗？  
从节点A出发，前往节点B的哪条路径最短？   

P82   
要按添加顺序查找    

P83  
队列   
队列类似于栈，  
不能随机访问队列中的元素   
队列只支持两种操作：  
入队和出队。   

队列是一种先进先出的数据结构  
而栈是一种后进后出的数据结构。  

运行时间  
O(人数+边数)  
O(V+E)    

 # 第六章小结    
	• 广度优先搜索指出是否有从A到B的路径。   
	• 如果有，广度优先搜索将找出最短路径。   
	• 面对最短路径问题时，可尝试使用图来建立模型，再使用广度优先搜索来解决问题。  
	• 有向图中的边为箭头，箭头的方向指定了关系的方向     
	• 无向图中的边不带箭头，其中的关系是双向的    
	• 队列是先进先出的    
	• 栈是后进后出的    
	• 要按加入顺序检查列表中的人，否则找到的就不是最短路径，      
	• 因此搜索列表必须是队列。      
	• 对于检查过的人，务必不要再去检查，否则可能导致无限循环。     
	
![image](https://user-images.githubusercontent.com/88927644/147747316-4680faa1-b3f8-451d-bd90-5f6958be9a49.png)
