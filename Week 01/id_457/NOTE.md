1. 移动零 ： loop {前移非零数据，{如果loop的index>目的index,loop的index的数据存为0}}
2. 盛最多水的容器：
方法一： 双loop；数组各元素两两组合，取最小的元素；当前面积=最小元素X组合的下标差；当前面积与历史最大面积比较，取最大值赋值给历史最大面积。loop结束后，输入 历史最大面积。
方法二：双指针法。（较好的实现方式）
                    
3.爬楼梯：f(n) = f(n-1)+f(n-2)

4.两数之和：
      方案1：嵌套双loop
      方案2：空间换时间-> 加入Map（散列表）
      
5.有效的括号:  栈（右括号入栈，有左括号时，pop()匹配，最终 判断栈是否空）

6.最小栈： 数据栈和辅助栈同步：辅助栈存放数据栈中最小值。

7.滑动窗口最大值: 双端队列 Deque

8.删除排序数组中的重复项: 数组为排序数组，若有重复元素，这些元素必定彼此相邻;双指针法（相邻指针）

9.旋转数组：环状替换

10.合并两个有序链表：修改指针

11.合并两个有序数组: 增加第三个数组，双指针（每次移动数值小的指针）

12.加一: 没看明白代码为什么那样不写

13.接雨水：官方题解 栈的应用 C++代码 改编的 Java代码

14 641. 设计循环双端队列：没看明白。
  
12，14  
