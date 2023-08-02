# 1. 基本信息

---
- Title: <%tp.file.title%>
- Created Date: <% tp.file.creation_date("YYYY-MM-DD ddd HH:mm:ss") %>
- Last Modified Date: <% tp.file.last_modified_date("YYYY-MM-DD ddd HH:mm:ss") %>
- Period: <%tp.date.now("YYYY-MM-DD ddd",0)%>  —— <%tp.date.now("YYYY-MM-DD ddd",6)%>
- Tags: #计划 #记录 #复盘 
---

# 2. <%tp.date.now("YYYY")%>W<%tp.date.now("WW")%>周计划

## 2.1 Q<%tp.date.now("Q")%> 目标细分任务




## 2.2 最重要日常事项（3—5个）

- [ ] 
- [ ] 
- [ ] 

# 3. <%tp.date.now("YYYY")%>W<%tp.date.now("WW")%>日程与日志

##  <%tp.date.now("MM-DD ddd",0)%>
1. 

##  <%tp.date.now("MM-DD ddd",1)%>
1. 

##  <%tp.date.now("MM-DD ddd",2)%>
1. 

##  <%tp.date.now("MM-DD ddd",3)%>
1. 

##  <%tp.date.now("MM-DD ddd",4)%>
1. 

##  <%tp.date.now("MM-DD ddd",5)%>
1. 

##  <%tp.date.now("MM-DD ddd",6)%>
1. 


# 4. <%tp.date.now("YYYY")%>W<%tp.date.now("WW")%>周复盘

## 4.1 回顾

### 	1.Q<%tp.date.now("Q")%> 计划完成情况



### 	2.日常事项完成情况



## 4.2 技能提升与经验积累

本周形成的笔记有：
```dataview
list 
where file.mtime >= date(today) - dur(6 days)
sort file.day
```


## 4.3 本周印象深刻事件



## 4.4 待办事项与下周计划

