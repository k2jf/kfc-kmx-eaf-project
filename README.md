# PasProjectDetail

## 功能
pas项目详情， 可重试

## 维护者
wangyanan

## 依赖
无

## 属性

| 属性        | 说明                                        | 类型   | 默认值 |
| ----------- | ------------------------------------------ | ------- | ------ |
| value       | 绑定v-model, true显示对话框, false隐藏对话框 | Boolean | false   |

## 示例
```
<template>
  <div>
    <PasProjectDetail v-model="projectId" />
  </div>
</template>

<script>
import PasProjectDetail from '@/kfc-project-detail/PasProjectDetail'
export default {
	components: {
		PasProjectDetail
	},
	data () {
		return {
			projectId: 102295
		}
	}
}
</script>
```