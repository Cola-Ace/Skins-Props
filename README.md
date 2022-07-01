# Skins-Props
说明: 支持Issues和Pull requests, 感谢你提交的每一个关于设置皮肤的方法(可提交源码示例)
| Prop类型 | Prop内容 | Prop作用 | Prop作用对象|Prop传值|
|:---------|:---------|:---------|:------------|:-------|
|Prop_Send|m_nFallbackPaintKit|设置Weapon(entity)皮肤|Weapon Entity|Skins_Index|
|Prop_Send|m_flFallbackWear|设置Weapon(entity)皮肤磨损(0.0-1.0)|Weapon Entity|Float|
|Prop_Send|m_nFallbackSeed|设置Weapon(entity)皮肤图案模板|Weapon Entity|Seed_Index|
|Prop_Send|m_nFallbackStatTrak|设置Weapon(entity)计数器(-1为无计数器)|Weapon Entity|Int|
|DataString|FindSendPropInfo("CBaseAttributableItem", "m_szCustomName")|设置Weapon(entity)名称|Weapon Entity|NameTag; StringSize|
|Prop_Send_Ent|m_hOwnerEntity|设置Weapon(entity)拥有者|Weapon Entity|Client_Index|
