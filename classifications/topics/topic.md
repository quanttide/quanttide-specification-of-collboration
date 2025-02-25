# 主题

## 定义

**主题（`Topic`）**是指在协作过程中讨论或处理的一个具体领域或话题。主题可以涵盖广泛的内容，从项目管理到技术实现，从市场营销到客户服务等。

## 属性

字段定义如下：

- **ID（`id`）** ：一个唯一的标识符，用于引用特定的主题。
- **创建时间（`created_at`）**： 主题创建的日期和时间。
- **更新时间（`updated_at`）**：主题最后修改的日期和时间。
- **标题（`title`）**： 主题的简短描述性标题。
- **内容（`content`）**：主题的具体内容。
- **状态（`status`）**：主题的当前状态。
- **优先级（`priority`）**：主题的优先级，用于确定讨论的顺序或重要性。

## 事件

#### 主题已创建（`TopicCreated`）

当一个新主题被创建时触发。包含以下属性：

- **ID（`id`）**：主题的唯一标识符。
- **创建时间（`created_at`）**：主题创建的日期和时间。
- **标题（`title`）**：主题的标题。
- **内容（`content`）**：主题的具体内容。
- **状态（`status`）**：主题的当前状态。
- **优先级（`priority`）**：主题的优先级。

#### 主题已更新（`TopicUpdated`）

当一个主题被更新时触发。包含以下属性：

- **ID（`id`）**：主题的唯一标识符。
- **更新时间（`updated_at`）**：主题最后修改的日期和时间。
- **标题（`title`）**：更新后的标题。
- **内容（`content`）**：更新后的具体内容。
- **状态（`status`）**：更新后的状态。
- **优先级（`priority`）**：更新后的优先级。

#### 主题已删除（`TopicDeleted`）

当一个主题被删除时触发。包含以下属性：

- **ID（`id`）**：主题的唯一标识符。
- **删除时间（`deleted_at`）**：主题删除的日期和时间。
