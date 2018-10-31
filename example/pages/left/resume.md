---
title: 我的简历 | 陈磊
name: 陈磊

baseinfo_name: "基本信息"
baseinfo:
    - line: "出生于1990年1月"
    - line: "性别：男"
contact_name: "联系方式"
contact: 
    - line: "邮箱：421524340@qq.com"
    - line: "手机：15072314647"
social_name: "社交信息"
social:
    - line: "微信：cl15072314647"
    - line: "QQ：421524340"
school_name: "教育背景"
school:
    - line: "毕业院校: 郑州大学（西亚斯国际学院）"
    - line: "本科 软件工程"

sitemap:
    changefreq: weekly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: 陈磊的个人简历。
    limit: 10
---

