<template>
	<div id="echarts1">
		<div class="myChart" :style="{width:'300px',height:'300px'}"></div>
	</div>
</template>
<script>
	let echarts = require('echarts/lib/echarts');
	require('echarts/lib/chart/bar');
	require('echarts/lib/component/tooltip');
	require('echarts/lib/component/toolbox');
	require('echarts/lib/component/legend');
	require('echarts/lib/component/markLine');
</script>