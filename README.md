# 基于ThreeJs封装的地图组件

# 安装
```bash
npm install @tntv/three-map --save
```

# 如何使用
```jsx
import ThreeMap from "@tntv/three-map";

// 初始化地图
const dom = document.getElementById('myMap');
const map = new ThreeMap({}, geojson);
map.init(dom);

```
