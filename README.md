# 数据库SQL实战

|选项|说明|
|:--:|:--:|
|:monkey_face:|表示通过|



| 编号 | 分类 |       标题       |  提交   |
| :--: | :--: | :--------------: | :---: |
|  1   |  | [查找最晚入职员工的所有信息](1.查找最晚入职员工的所有信息.md) | :monkey_face: |
| 2 |  | [查找入职员工时间排名倒数第三的员工所有信息](2.查找入职员工时间排名倒数第三的员工所有信息.md) | :monkey_face: |
| 3 |  | [查找当前薪水详情以及部门编号dept_no](3.查找当前薪水详情以及部门编号dept_no.md) | :monkey_face: |
| 4 |  | [查找所有已经分配部门的员工的last_name和first_name](4.查找所有已经分配部门的员工的last_name和first_name.md) | :monkey_face: |
| 5 |  | [查找所有员工的last_name和first_name以及对应部门编号dept_no](5.查找所有员工的last_name和first_name以及对应部门编号dept_no.md) | :monkey_face: |
| 6 |  | [查找所有员工入职时候的薪水情况](6.查找所有员工入职时候的薪水情况.md) | :monkey_face: |
| 7 |  | [查找薪水涨幅超过15次的员工号emp_no以及其对应的涨幅次数t](7.查找薪水涨幅超过15次的员工号emp_no以及其对应的涨幅次数t.md) | :monkey_face: |
| 8 |  | [找出所有员工当前薪水salary情况](8.找出所有员工当前薪水salary情况.md) | :monkey_face: |
| 9 |  | [获取所有部门当前manager的当前薪水情况，给出dept_no, emp_no以及salary，当前表示to_date=9999-01-01](9.获取所有部门当前manager的当前薪水情况，给出dept_no, emp_no以及salary，当前表示to_date='9999-01-01'.md) | :monkey_face: |
| 10 |  | [获取所有非manager的员工emp_no](10.获取所有非manager的员工emp_no.md) | :monkey_face: |
| 11 |  | [获取所有员工当前的manager](11.获取所有员工当前的manager.md) | :monkey_face: |
| 12 |  | [获取所有部门中当前员工薪水最高的相关信息](12.获取所有部门中当前员工薪水最高的相关信息.md) | 5​.​8:see_no_evil::monkey_face: |
| 13 |  |  |  |
| 14 |  |  |  |
| 15 |  |  |  |
| 16 |  |  |  |
| 17 |  |  |  |
| 18 |  |  |  |
| 19 |  |  |  |
| 20 |  |  |  |
| 21 |  |  |  |
| 22 |  |  |  |
| 22.1 |  |  |  |
| 23 |  |  |  |
| 24 |  |  |  |
| 25 |  |  |  |
| 26 |  |  |  |
| 27 |  |  |  |
| 28 |  |  |  |
| 29 |  |  |  |
| 30 |  |  |  |
| 31 |  |  |  |
| 32 |  |  |  |
| 33 |  |  |  |
| 34 |  |  |  |
| 35 |  |  |  |
| 36 |  |  |  |
| 37 |  |  |  |
| 38 |  |  |  |
| 39 |  |  |  |
| 40 |  |  |  |
| 41 |  |  |  |
| 42 |  |  |  |
| 43 |  |  |  |
| 44 |  |  |  |
| 45 |  |  |  |
| 46 |  |  |  |
| 47 |  |  |  |
| 48 |  |  |  |
| 49 |  |  |  |
| 50 |  |  |  |
| 51 |  |  |  |
| 52 |  |  |  |
| 53 |  |  |  |
| 54 |  |  |  |
| 55 |  |  |  |
| 56 |  |  |  |
| 57 |  |  |  |
| 58 |  |  |  |
| 59 |  |  |  |
| 60 |  |  |  |
| 61 |  |  |  |

**答案全部在牛客网测试通过。语法规格MySQL5.8**

题解主要有参考[牛课网论坛](https://www.nowcoder.com/ta/sql)



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