---
layout:center
class:'siwei'
---
# 项目六大管理
<style>
.siwei {
    height: 50%;
}
</style>
<div v-click v-motion 
  :initial="{ x: 100,y:-70 }"
  :enter="{ x: 100 }">
```mermaid
graph LR
A[六大管理] -->B(项目流程管理)
          A-->C(项目沟通管理)
          A-->D(项目时间管理)
          A-->E(项目资源管理)
          A-->F(项目质量管理)
          A-->G(项目风险管理)
```
</div>
