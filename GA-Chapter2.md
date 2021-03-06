第二章 选择排序

## 本章内容：    
	1. 学习两种最基本的数据结构-数组和链表。  
	所有章节都将用到数组。数组是个重要的主题，一定要高度重视！  
	但在有些情况下，使用链表比使用数组更合适。  
	本章阐述数组和链表的优缺点  
	让你能够根据要实现的算法选择合适的一个。  
	
	2. 学习第一种排序算法。  
	很多算法仅在数据经过排序后才管用。  
	
	比如二分查找只能用于有序元素列表。  
	本章将介绍选择排序。  
	很多语言都内置了排序算法，  
	因此你基本上不用从头开始编写自己的版本。  
	
	但选择排序是快速排序的基石。   
	快速排序是一种重要的算法。  
	
 ## 内存的工作原理  
计算机就像是很多抽屉的集合体  
每个抽屉都有地址  

 ## 数组和链表  
 ### 链表     
链表的每个元素都储存了下一个元素的地址，  
从而使一系列随机的内存地址串在一起。   
使用链表时，根本就不需要移动元素。   
链表相当于说：“我们分开来坐”  
因此，只要有足够的内存空间，就能为链表分配内存。  
链表的优势在插入元素方面。   

 ### 数组  
需要同时读取所有元素时，  
链表的效率很高  
但如果你需要跳跃  
链表的效率真的很低。  

数组与此不同：你知道其中每个元素的地址     
需要随机地读取元素时，数组的效率很高。   
因为可迅速找到数组的任何元素。   


数组的元素带编号  
编号从0而不是1开始  
几乎所有的编程语言都是这样  

元素的位置称为索引  
本书将使用索引来表示位置  

 ## 需要在中间插入元素时  
使用链表时，只需修改它前面的那个元素指向的地址。  
使用数组时，必须将后面的元素都向后移。  

 ## 删除     
链表也是更好的选择  
因为只需修改前一个元素指向的地址即可  

而使用数组时，删除元素后  
必须将后面的元素都向前移。  

不同于插入，删除元素总能成功。  
如果内存没有足够的空间，插入操作可能失败，  
但在任何情况下 都能够将元素删除。  


数组和链表哪个用的更多呢？  
显然要看情况。  
但数组用的很多，因为他支持随机访问。    

有两种访问方式：  
随机访问和顺序访问。  
 链表只能顺序访问：  
要读第十个元素，得先读取前九个  
随机访问意味着可直接跳到第十个元素  

本书经常说数组的读取速度更快，  
这是因为他们支持随机访问  
很多情况都要求能够随机访问，因此数组用得很多。     

数组和链表还被用来实现其他数据结构，  
这将在本书后面介绍。   

P25  
 ## 选择排序    

 # 第三章小结  
计算机内存犹如一大堆抽屉。  
需要存储多个元素时，可使用数组或链表。  
数组的元素都在一起。    
链表的元素是分开的，其中每个元素都存储了下一个元素的地址。    
数组的读取速度很快。  
链表的插入和删除速度很快。   
在同一个数组中，所有元素的类型都必须相同。  （都为int、double等）
