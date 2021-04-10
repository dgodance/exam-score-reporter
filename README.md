# 中学生考试成绩记录小程序
给妹妹做的一个记录每次考试的成绩小程序，以便于知道每次考试的详细情况。基于
[uniapp-tailwind-uview-starter](https://github.com/xlzy520/uniapp-tailwind-uview-starter)



### changeLog
主要修复1. 修复一直提示填写考试名称
2. 增加大学、小学



### 主要功能
- 课程配置
  - 自定义课程配置
  - 满分配置
- 成绩登记
  - 平均分
  - 总分
  - 班级排名
  - 年级排名
- 记录查看
  - 按年级分组查看
  - 图表查看(未完成)
  - 两次考试成绩对比(未完成)
  
### TODO
1. 图表查看总成绩、排名或单科成绩的变化曲线
2. 考试成绩对比(总成绩、排名或单科成绩)


### install
1. 云函数文件存储在`static/cloudfunctions-tcb`中
2. 云数据库表: `scores`，`gradeSubject`，`users`, `report`
