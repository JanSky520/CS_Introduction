# 练习题

1. 略
2. 略
3. 略
4. 略
5. 略
6. select No, Unit from 课程;  
7. select ID, Name from 学生;
8. select ID, Name from 教授;
9. select Name from 系;
10. select ID, Courses from 学生 where ID = 2010;
11. select Name, Courses from 教授 where Name = "Blake";
12. select * from 课程 where Unit = 3;
13. select * from 学生 where Courses = "CIS015";
14. select No from 系 where Name = "计算机科学系";
15. 略
16. 略
17. 略
18. 略
19. 第三范式：在2NF的基础上，非主键之间相互独立，不能产生函数依赖。简单地讲就是不能留有传递函数依赖
20. BC范式：在3NF的基础上，主属性内不能存在函数依赖