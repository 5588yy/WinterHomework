使用注意事项：

1、在上传作业之前需先进入管理员模式（id：000000，password：123456，name：none）设置作业储存位置。

2、默认系统内无成员，在管理员模式内可加入成员。

test信息【放在User的judge方法中】

```java
//test
stu_number.add("0002");
stu_password.put("0002","0002");
tea_number.add("0001");
tea_password.put("0001","0001");
Homework homework=new Homework();
this.workpath="C:\\homework";
```

3、由于只有自己写的一个后端，没有结合前端，所以以复制文件到指定文件夹的方式提交作业

4、检查作业为直接打开某同学的作业/打开指定文件夹【可看到所有人的作业】

5、User中管理所有成员及其权限

6、代码在HomeworkSystem中的System中