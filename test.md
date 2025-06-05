```plantuml
@startuml
skinparam backgroundColor #EEEBDC
entity "用户表" {
  *用户ID
  --
  用户名
  邮箱
}
用户表 }|--|| 订单表 : 1对多
@enduml
```
