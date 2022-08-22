- 为什么使用 Pinia ?
- 在 Vue3,  可以通过简单的使用 `export const state = reactive({})` 来做跨组件/页面共享状态. 但如果是 SSR, 会暴露安全漏洞.
- Pinia 特性:
	- 开发工具支持 ✔
		- 跟踪动作、突变的时间线
		- Store 出现在使用它们的组件中
		- time travel 和 更容易的调试
	- 热模块替换
		- 在不重新加载页面的情况下, 修改 Store
		- 在开发时保持任何现有状态
	- 插件
		- 使用插件扩展 Pinia 功能
		- 为 JS 用户提供适当的 TypeScript 支持或 autocompletion?
		- 服务器端渲染支持
- ps: 对于小型应用来说, 上述除了开发工具支持, 更好调试, 没什么用.
- [[RFC]]是什么?