# ECHARTS-3.0 细节知识

## 柱状图

- 同一系列中柱子颜色不同

  `series-bar.itemStyle.color`

  ```javascript
  color: function (params) {
  	var colorList = ["#FF5200", "#FFC45F", "#1A6AC5", "#00E3E3", "#379E65"]
  	return colorList[params.dataIndex]
  }
  ```

  

- 