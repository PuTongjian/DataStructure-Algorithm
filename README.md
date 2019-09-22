# 数据结构和算法
### 从原理到代码实现，一步步掌握常用的数据结构和算法。

---

## 数组（Array）
数组是一种**顺序存储结构**，当数组被声明时它会划分出一块连续的地址。正因为它是连续的，利用元素的索引（index）可以计算出该元素对应的存储地址。 

![数组.gif](https://images2018.cnblogs.com/blog/772743/201804/772743-20180410233420469-136207805.gif)  

**优点：**
- 无论数组有多大，根据索引位置只需要一次操作就可货取元素的内容，**查询效率高**。数组的**查询**操作的**时间复杂度为O(1)**。 

**缺点：**
- 同样因为数组的内存地址是连续的，插入（删除）一个元素时，该元素的所有后继元素都要挪动位置，所以**插入和删除操作效率低下**。数组的**插入和删除**操作**时间复杂度为O(n)**。
![插入.gif](https://images2018.cnblogs.com/blog/772743/201804/772743-20180410235302025-1349081730.gif)
- 大小固定，不支持扩展。

注意：当**有序线性表**查找的**时间复杂度为O(1)** 时，折中查找的**时间复杂度为O(logN)**。

---

## 链表(Linked list)
链表是一种**链式存储结构**，它是一种**线性表**，但是并不会按线性的顺序存储数据，而是在每一个节点里存到下一个节点的指针(Pointer)，将一些不连续的内存空间串连起来。  

**优点：**
- 链表在插入和删除操作时只需要改变某一结点的指针域，所以**插入和删除操作效率高**，**时间复杂度为O(1)**。
- 大小不固定，支持扩展。

**缺点：**
- **索引访问慢**，**时间复杂度为O(n)**

### [单向链表](https://github.com/PuTongjian/DataStructure-Algorithm/blob/master/data_structure/linked_list.py)
![链表.png](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Singly-linked-list.svg/408px-Singly-linked-list.svg.png)  
链表中最简单的一种是**单向链表**，它包含两个域，一个信息域和一个指针域。这个链接指向列表中的下一个节点，而最后一个节点则指向一个空值。

### [双向链表]()
![双向链表.png](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Doubly-linked-list.svg/610px-Doubly-linked-list.svg.png)  
在单向链表的基础上，每个节点有两个两个指针，一个指向前驱节点，另一个指向后驱节点。

### [循环链表]()
![循环链表.png](https://upload.wikimedia.org/wikipedia/commons/thumb/d/df/Circularly-linked-list.svg/350px-Circularly-linked-list.svg.png)  
普通链表的尾节点后继指针指向`None`，而循环链表的尾节点后继指针指向头节点

## 栈（LIFO, Last In First Out）
堆栈（stack）又称为栈或堆叠，是一种抽象数据类型，只允许在有序的线性数据集合的一端（堆栈顶端, top）进行加入数据（push）和移除数据（pop）的运算。因而按照后进先出（LIFO, Last In First Out）的原理运作。  
![栈.jpg](http://chuantu.xyz/t6/702/1569165698x2073513213.jpg)
## 队列

## 优先队列

## 哈希表

## 二叉树和二叉搜索树

## 
