# 介绍
本课程的目标是让你掌握正确，高效的方法，去解决计算问题。
# 问题
 + 问题输入和正确输出的关系
 + 通常不会用面向测试样例的方法。
 + 正确的输出必须满足：可以被有效的验证。
 + 学习解决常见的，复杂情况的问题。
 + 不通用的问题：
    * 例如：在这间屋子内，有多少对同学有相同的生日
 + 通用的问题
    * 例如：求解n个同学，在同一天生日的概率

# 算法
 + 对每一个问题求解出唯一的，确定的结果。
 + 如果可以返回正确的答案针对每个问题，那么该算法解决了这个问题。
 + 例如：一种求解生日匹配的算法
    * 维护姓名和生日的记录(初始化为空)
    * 以某种顺序访问每一个学生
        * 如果生日在记录中匹配，返回解决。
        * 否则将姓名和生日添加到记录中。
    * 返回空，如果没有匹配的学生。

# 正确性
 + 程序/算法的大小是固定的，那么如何证明它是正确的呢？
 + 对于小问题，可以分析每一种情况。
 + 对于任意大的输入，算法必须是递归的或以某种方式循环。
 + 必须使用归纳法(为什么递归是计算机科学中如此重要的概念)
 
# 效率
 + 算法得到正确结果的速度有多快？?
    * 可以测量时间，但希望性能独立于机器
    * 计算固定时间操作算法返回的次数
    * 期望取决于输入的大小：更大的输入意味着更长的时间
    * 输入的大小通常称为“n”，但并非总是如此！
    * 如果在多项式时间内相对于输入返回是有效的
    * 有时不存在解决问题的有效算法！ （见 L20）
 + 渐近符号：忽略常数因子和低阶项（时间复杂度分析）
    ![](/img/time.png)
