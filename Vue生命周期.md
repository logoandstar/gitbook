### Vue生命周期
- #### 挂载阶段
* ##### create：此阶段vue实例已创建（创建前）
* ##### beforeCreate:此阶段为实例初始化之后（创建后）
* ##### mounted：组建绘制完成，数据和DOM都已渲染出来（载入前）
* ##### beforeMount:vue挂载的根节点已创建（载入后）
* ##### Updata:DOM会和更改过的内容同步（更新前）
* ##### beforeUpdata:beforeUpdata函数在数据更新后没有立即更新数据（更新后）
* ##### destroyed：（销毁前）
* ##### beforedestroyed：（销毁后）