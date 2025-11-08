# 前言

欢迎来到基于SSM的在线试卷生成系统项目仓库！本项目旨在为教育工作者和学生提供一个便捷、高效的在线试卷生成平台，实现自动化组卷、阅卷等功能，减轻教师工作负担，提高学生学习效率。

# 内容介绍

基于SSM的在线试卷生成系统主要包括以下模块：用户管理、题库管理、试卷管理、考试管理、阅卷管理等。系统采用Java语言，结合Spring、SpringMVC、MyBatis框架，以及前端技术Vue、JS和CSS3进行开发。通过本系统，教师可以轻松创建试卷、发布考试，学生可以在线答题、查看成绩，实现教学活动的线上化、智能化。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下是试卷管理模块中的一段核心代码，用于查询试卷列表：

```java
@RequestMapping(value = "/list", method = RequestMethod.GET)
public String list(Model model, @RequestParam(value = "page", defaultValue = "1") int page,
                   @RequestParam(value = "size", defaultValue = "10") int size) {
    PageHelper.startPage(page, size);
    List<Paper> papers = paperService.list();
    PageInfo<Paper> pageInfo = new PageInfo<>(papers);
    model.addAttribute("papers", papers);
    model.addAttribute("pageInfo", pageInfo);
    return "paper/list";
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/329700/8/11494/163682/68c06d02F83bb7ad0/60db88f7e5b7b412.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/331638/2/11416/19128/68c06cdaF6fcdac88/0667b086b5c83112.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324331/13/18111/115772/68c06cdaF8e40bba7/cf3b8c341430c47c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326343/6/18124/21456/68c06cdbFc4e514aa/28e5746fbd4e1d4b.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/346906/27/1579/17635/68c06cdbFba502f2b/49de30f5c9d22c0f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/344101/31/1566/25238/68c06cdcF25f5af04/b74eab73f6a344c6.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345561/4/1243/35357/68c06cdcF7e79c800/64baa8ee56644647.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337213/12/5098/13933/68c06cdcF60ad6bd9/a08dcbb8b45bcc95.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/346972/38/1538/112094/68c06cddF51561aff/0d1332b32c08168d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336146/38/8917/43937/68c06cddF2bea0ada/3ddc8709e71eb8ec.jpg)

