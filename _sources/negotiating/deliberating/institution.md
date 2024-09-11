# 议事机构 

议事机构(`DeliberativeInstitution`)，通常指的是一个正式的组织或团体，其成员聚集在一起讨论、审议和决定特定的事务或政策。
这类机构可能存在于政府、企业、非营利组织或其他类型的治理结构中。
议事机构的目的是为了集思广益，通过成员之间的讨论和辩论，最终形成决策。

例如：

* 政府机构：国会、议会、国民议会、立法院等。
* 企业机构：董事会、监事会、股东大会等。
* 非营利组织：理事会、咨询委员会等。

字段：

- ID(`id`) 
- 创建时间(`createdAt`) 
- 更新时间(`updatedAt`) 
- 标识(`name`) 
- 名称(`verboseName`)

## 汇报关系

议事机构汇报关系(`DeliberativeInstitutionRelation`) 

字段：

- ID(`id`)
- 创建时间(`createdAt`) 
- 子机构(`child`) 
- 父机构(`parent`)