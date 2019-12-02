# 数据库SQL实战

|选项|说明|
|:--:|:--:|
|:monkey_face:|通过|
|:see_no_evil:|未通过或不符合MySQL5.7语法规范|



| 编号 | 分类 |       标题       |  提交   |
| :--: | :--: | :--------------: | :---: |
|  1   | 过滤 | [查找最晚入职员工的所有信息](1.查找最晚入职员工的所有信息.md) | :monkey_face: |
| 2 | 过滤 | [查找入职员工时间排名倒数第三的员工所有信息](2.查找入职员工时间排名倒数第三的员工所有信息.md) | :monkey_face: |
| 3 | 连接 | [查找当前薪水详情以及部门编号dept_no](3.查找当前薪水详情以及部门编号dept_no.md) | :monkey_face: |
| 4 | 连接 | [查找所有已经分配部门的员工的last_name和first_name](4.查找所有已经分配部门的员工的last_name和first_name.md) | :monkey_face: |
| 5 | 连接 | [查找所有员工的last_name和first_name以及对应部门编号dept_no](5.查找所有员工的last_name和first_name以及对应部门编号dept_no.md) | :monkey_face: |
| 6 | 连接 | [查找所有员工入职时候的薪水情况](6.查找所有员工入职时候的薪水情况.md) | :monkey_face: |
| 7 | 分组 | [查找薪水涨幅超过15次的员工号emp_no以及其对应的涨幅次数t](7.查找薪水涨幅超过15次的员工号emp_no以及其对应的涨幅次数t.md) | :monkey_face: |
| 8 | 过滤 | [找出所有员工当前薪水salary情况](8.找出所有员工当前薪水salary情况.md) | :monkey_face: |
| 9 | 连接 | [获取所有部门当前manager的当前薪水情况，给出dept_no, emp_no以及salary，当前表示to_date=9999-01-01](9.获取所有部门当前manager的当前薪水情况.md) | :monkey_face: |
| 10 | 过滤 | [获取所有非manager的员工emp_no](10.获取所有非manager的员工emp_no.md) | :monkey_face: |
| 11 | 连接 | [获取所有员工当前的manager](11.获取所有员工当前的manager.md) | :monkey_face: |
| 12 | 分组聚合 | [获取所有部门中当前员工薪水最高的相关信息](12.获取所有部门中当前员工薪水最高的相关信息.md) | :see_no_evil: |
| 13 | 分组聚合 | [从titles表获取按照title进行分组](13.从titles表获取按照title进行分组.md) | :monkey_face: |
| 14 | 分组聚合 | [从titles表获取按照title进行分组](14.从titles表获取按照title进行分组2.md) | :monkey_face: |
| 15 | 过滤 | [查找employees表](15.查找employees表.md) | :monkey_face: |
| 16 | 分组聚合 | [统计出当前各个title类型对应的员工当前薪水对应的平均工资](16.统计出当前各个title类型对应的员工当前薪水对应的平均工资.md) | :monkey_face: |
| 17 | 过滤 | [获取当前薪水第二多的员工的emp_no以及其对应的薪水salary](17.获取当前薪水第二多的员工的emp_no以及其对应的薪水salary.md) | :monkey_face: |
| 18 | 连接 | [获取当前薪水第二多的员工的emp_no以及其对应的薪水salary，不准使用order by](18.获取当前薪水第二多的员工的emp_no以及其对应的薪水salary2.md) | :monkey_face: |
| 19 | 连接 | [查找所有员工的last_name和first_name以及对应的dept_name](19.查找所有员工的last_name和first_name以及对应的dept_name.md) | :monkey_face: |
| 20 | 过滤 | [查找员工编号emp_no为10001其自入职以来的薪水salary涨幅值growth](20.查找员工编号emp_no为10001其自入职以来的薪水salary涨幅值growth.md) | :monkey_face: |
| 21 | 连接 | [查找所有员工自入职以来的薪水涨幅情况](21.查找所有员工自入职以来的薪水涨幅情况.md) | :monkey_face: |
| 22 | 分组聚合 | [统计各个部门对应员工涨幅的次数总和](22.统计各个部门对应员工涨幅的次数总和.md) | :monkey_face: |
| 23 | 排名 | [对所有员工的薪水按照salary进行按照1-N的排名](23.对所有员工的薪水按照salary进行按照1-N的排名.md) | :see_no_evil: |
| 24 | 连接 | [获取所有非manager员工当前的薪水情况](24.获取所有非manager员工当前的薪水情况.md) | :monkey_face: |
| 25 | 连接 | [获取员工其当前的薪水比其manager当前薪水还高的相关信息](25.获取员工其当前的薪水比其manager当前薪水还高的相关信息.md) | :monkey_face: |
| 26 | 连接和分组 | [汇总各个部门当前员工的title类型的分配数目](26.汇总各个部门当前员工的title类型的分配数目.md) | :monkey_face: |
| 27 | 连接 | [给出每个员工每年薪水涨幅超过5000的员工编号emp_no](27.给出每个员工每年薪水涨幅超过5000的员工编号emp_no.md) | :see_no_evil: |
| 28 | 连接 | [查找描述信息中包括robot的电影对应的分类名称以及电影数目，而且还需要该分类对应电影数量>=5部](28.查找描述信息中包括robot的电影对应的分类名称以及电影数目.md) | :monkey_face: |
| 29 | 连接 | [使用join查询方式找出没有分类的电影id以及名称](29.使用join查询方式找出没有分类的电影id以及名称.md) | :monkey_face: |
| 30 | 子查询 | [使用子查询的方式找出属于Action分类的所有电影对应的title,description](30.使用子查询.md) | :monkey_face: |
| 31 | 优化 | [获取 select * from employees 对应的执行计划](31.获取select对应的执行计划.md) | :monkey_face: |
| 32 | 字符串处理 | [将employees表的所有员工的last_name和first_name拼接起来作为Name](32.将employees表的所有员工的last_name和first_name拼接起来作为Name.md) | :see_no_evil: |
| 33 | 表操作 | [创建一个actor表，包含如下列信息](33.创建一个actor表.md) | :see_no_evil: |
| 34 | 数据操作 | [批量插入数据](34.批量插入数据.md) | :monkey_face: |
| 35 | 数据操作 | [批量插入数据，不使用replace操作](35.批量插入数据不使用replace操作.md) | :see_no_evil: |
| 36 | 表和数据操作 | [创建一个actor_name表](36.创建一个actor_name表.md) | :monkey_face: |
| 37 | 索引 | [对first_name创建唯一索引uniq_idx_firstname](37.对first_name创建唯一索引uniq_idx_firstname.md) | :monkey_face: |
| 38 | 视图 | [针对actor表创建视图actor_name_view](38.针对actor表创建视图actor_name_view.md) | :monkey_face: |
| 39 | 索引 | [针对上面的salaries表emp_no字段创建索引idx_emp_no](39.针对上面的salaries表emp_no字段创建索引idx_emp_no.md) | :see_no_evil: |
| 40 | 表操作 | [在last_update后面新增加一列名字为create_date](40.在last_update后面新增加一列名字为create_date.md) | :see_no_evil: |
| 41 | 触发器 | [构造一个触发器audit_log](41.构造一个触发器audit_log.md) | :monkey_face: |
| 42 | 数据操作 | [删除emp_no重复的记录，只保留最小的id对应的记录](42.删除emp_no重复的记录只保留最小的id对应的记录.md) | :monkey_face: |
| 43 | 数据操作 | [将所有to_date为9999-01-01的全部更新为NULL](43.将所有to_date为9999-01-01的全部更新为NULL.md) | :monkey_face: |
| 44 | 数据操作 | [将id=5以及emp_no=10001的行数据替换成id=5以及emp_no=10005](44.将id=5以及emp_no=10001的行数据替换成id=5以及emp_no=10005.md) | :monkey_face: |
| 45 | 表操作 | [将titles_test表名修改为titles_2017](45.将titles_test表名修改为titles_2017.md) | :monkey_face: |
| 46 | 外键 | [在audit表上创建外键约束，其emp_no对应employees_test表的主键id](46.在audit表上创建外键约束其emp_no对应employees_test表的主键id.md) | :monkey_face: |
| 47 | 连接 | [如何获取emp_v和employees有相同的数据no](47.如何获取emp_v和employees有相同的数据no.md) | :monkey_face: |
| 48 | 数据操作 | [将所有获取奖金的员工当前的薪水增加10%](48.将所有获取奖金的员工当前的薪水增加10%.md) | :monkey_face: |
| 49 | 字符串处理 | [针对库中的所有表生成select count(*)对应的SQL语句](49.针对库中的所有表生成对应的SQL语句.md) | :see_no_evil: |
| 50 | 字符串处理 | [将employees表中的所有员工的last_name和first_name通过(')连接起来](50.将employees表中的所有员工的last_name和first_name通过连接起来.md) | :see_no_evil: |
| 51 | 字符串处理 | [查找字符串'10,A,B' 中逗号','出现的次数cnt](51.查找字符串.md) | :monkey_face: |
| 52 | 字符串处理 | [获取Employees中的first_name](52.获取Employees中的first_name.md) | :monkey_face: |
| 53 | 聚合函数 | [按照dept_no进行汇总](53.按照dept_no进行汇总.md) | :monkey_face: |
| 54 | 聚合函数 | [查找排除当前最大、最小salary之后的员工的平均工资avg_salary](54.查找排除当前最大最小salary之后的员工的平均工资avg_salary.md) | :monkey_face: |
| 55 | 关键字 | [分页查询employees表，每5行一页，返回第2页的数据](55.分页查询employees表.md) | :monkey_face: |
| 56 | 连接 | [获取所有员工的emp_no](56.获取所有员工的emp_no.md) | :monkey_face: |
| 57 | 子查询 | [使用含有关键字exists查找未分配具体部门的员工的所有信息](57.使用含有关键字exists查找未分配具体部门的员工的所有信息.md) | :monkey_face: |
| 58 | 视图 | [获取employees中的行数据，且这些行也存在于emp_v中](58.获取employees中的行数据且这些行也存在于emp_v中.md) | :monkey_face: |
| 59 | 条件语句 | [获取有奖金的员工相关信息](59.获取有奖金的员工相关信息.md) | :monkey_face: |
| 60 | 表的复用 | [统计salary的累计和running_total](60.统计salary的累计和running_total.md) | :monkey_face: |
| 61 | 表的复用 | [对于employees表中，给出奇数行的first_name](61.对于employees表中给出奇数行的first_name.md) | :see_no_evil: |

**答案全部在牛客网测试通过。语法规格SQLite3.7.9**

题解主要有参考[牛课网论坛](https://www.nowcoder.com/ta/sql)

本地测试使用**MySQL5.7**，部分语法与**SQLite**存在差异，对于MySQL5.7+，请设置**sql_mode**，正确使用group by(解决**ONLY_FULL_GROUP_BY**导致的group by查询条件严苛问题，此方法只做临时修改)

```mysql
set sql_mode=(select replace(@@sql_mode,'ONLY_FULL_GROUP_BY','')); 
```

详情参考:[MySQL的sql_mode解析与设置](https://www.cnblogs.com/fireporsche/p/8618691.html)

## 离线练习数据集配置

> 牛客网的数据结构几乎与MySQL测试用的数据集相通，可以先在本地测试后，再在牛客网提交结果

1. 前往 https://launchpad.net/test-db/employees-db-1/1.0.6 下载文件 **employees_db-full-1.0.6.tar.bz2**

2. 解压缩下载的文件

   ```bash
   tar jxvf employees_db-full-1.0.6.tar.bz2
   cd employees_db-full-1.0.6
   ```

3. 修改文件 employees.sql

   ```bash
   # 38行 set storage_engine = InnoDB; 替换
   set default_storage_engine = InnoDB;
   # 44行 select CONCAT('storage engine: ', @@storage_engine) as INFO; 替换
   select CONCAT('storage engine: ', @@default_storage_engine) as INFO;
   ```

4. 导入数据库

   ```bash
   mysql -uroot -p -t < employees.sql
   ```

参考:https://blog.csdn.net/appleyuchi/article/details/79439387

GitHub:https://github.com/datacharmer/test_db
