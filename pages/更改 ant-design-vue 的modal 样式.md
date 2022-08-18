- 一般深度选择器不能解决的都是像 el-select 那样, DOM 不在挂载的元素下边, 比如说 \#app.
- 利用组件库提供的 getContainer API, 将其置入 \#app 里边, 实现如下:
- ```
  <div ref="con">
      <a-modal
            v-model="visible"
            :footer="null"
            :get-container="()=>this.$refs.con"
            @ok="handleOk"
          >
      </a-modal>
  <div>
  
  作者：嚣张农民
  链接：https://juejin.cn/post/7005023139428040735
  来源：稀土掘金
  著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
  ```
- 另附上 [[Vue 深度选择器的使用]]