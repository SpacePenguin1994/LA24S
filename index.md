---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: Linear Algebra, SHNU
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

Linear algebra is the branch of mathematics concerning linear equations such as:
- $a_1x_1 + a_2x_2 + \cdots + a_nx_n = b$,

linear maps such as:

- $(x_1,\ldots,x_n)\rightarrow a_1x_1 + a_2x_2 + \cdots + a_nx_n$

In fact, it's central to almost all areas of mathematics. In this course, we will follow the idea of solving linear equations $A\mathbf{x}=\mathbf{b}$ and introduce the four fundamental subspaces for the matrix $A$. Hence we'll show the fundamental theorem of linear algebra.

Enjoy the class!

See the [Syllabus page](syllabus.md) for more details on course policies.

## General Information

**Instructor:** [Qizhe Yang](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**Time and Location:**

- For the class 1 of Computer Science and Technology (Teaching Training):
  - &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &nbsp;Every Monday in Week 1-16, &nbsp;&nbsp;&nbsp;&nbsp;&thinsp; 奉贤3教楼316
  - &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &nbsp;Every <font color="#dd0000">odd Friday</font> in Week 1-15，奉贤3教楼101
- For the class 1 of Electronic Information:
  - &ensp;&nbsp;13:00 p.m.- 14:30 p.m. &nbsp;Every Monday in Week 1-16, &emsp;&ensp;&nbsp;&thinsp;&thinsp;奉贤3教楼416
  - &ensp;&nbsp;8:00 a.m.- 9:30 a.m. &emsp;&nbsp; Every <font color="#dd0000">even Friday</font> in Week 2-16， 奉贤3教楼112


 For more details about the class, see the [Schedule page](schedule.md).


## Course Feedback

We have set up a course questionnaire:

- [《线性代数》课程调查问卷](https://www.wjx.cn/vm/tU88Sco.aspx)

Everyone is welcome to submit his/her questions or suggestions about this course.

**Updated in Jun 6, 2022**

Since we will finish the course in the next week, we have set up a new questionnaire for collecting the feedback of this course:

- [《线性代数》完课调查问卷](https://www.wjx.cn/vm/rQggcUK.aspx#)

The questionnaire is not mandatory, but I will appreciate it if you can spend a few minutes to fill it out. Thank you!

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}