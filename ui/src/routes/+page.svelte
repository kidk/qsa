<script>
	import { Line } from 'svelte-chartjs'
	import 'chart.js/auto';

	export const data = {
		labels: ['January', 'February', 'March', 'April', 'May', 'June', 'July'],
		datasets: [
			{
				label: 'My First dataset',
				fill: true,
				lineTension: 0.3,
				backgroundColor: 'rgba(225, 204,230, .3)',
				borderColor: 'rgb(205, 130, 158)',
				borderCapStyle: 'butt',
				borderDash: [],
				borderDashOffset: 0.0,
				borderJoinStyle: 'miter',
				pointBorderColor: 'rgb(205, 130,1 58)',
				pointBackgroundColor: 'rgb(255, 255, 255)',
				pointBorderWidth: 10,
				pointHoverRadius: 5,
				pointHoverBackgroundColor: 'rgb(0, 0, 0)',
				pointHoverBorderColor: 'rgba(220, 220, 220,1)',
				pointHoverBorderWidth: 2,
				pointRadius: 1,
				pointHitRadius: 10,
				data: [65, 59, 80, 81, 56, 55, 40],
			},
			{
				label: 'My Second dataset',
				fill: true,
				lineTension: 0.3,
				backgroundColor: 'rgba(184, 185, 210, .3)',
				borderColor: 'rgb(35, 26, 136)',
				borderCapStyle: 'butt',
				borderDash: [],
				borderDashOffset: 0.0,
				borderJoinStyle: 'miter',
				pointBorderColor: 'rgb(35, 26, 136)',
				pointBackgroundColor: 'rgb(255, 255, 255)',
				pointBorderWidth: 10,
				pointHoverRadius: 5,
				pointHoverBackgroundColor: 'rgb(0, 0, 0)',
				pointHoverBorderColor: 'rgba(220, 220, 220, 1)',
				pointHoverBorderWidth: 2,
				pointRadius: 1,
				pointHitRadius: 10,
				data: [28, 48, 40, 19, 86, 27, 90],
			},
		],
	};

</script>

<div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center pt-3 pb-2 mb-3 border-bottom">
	<h1 class="h2">Dashboard</h1>
	<div class="btn-toolbar mb-2 mb-md-0">
		<div class="btn-group me-2">
			<button type="button" class="btn btn-sm btn-outline-secondary">Share</button>
			<button type="button" class="btn btn-sm btn-outline-secondary">Export</button>
		</div>
		<button type="button" class="btn btn-sm btn-outline-secondary dropdown-toggle d-flex align-items-center gap-1">
			This week
		</button>
	</div>
</div>

<div class="p4">
	<Line
			data={data}
			width={100}
			height={300}
			options={{ maintainAspectRatio: false }}
	/>
</div>

<h2 class="pt-3">Data</h2>
<div class="table-responsive small">
	<table class="table table-striped table-sm">
		<thead>
		<tr>
			<th scope="col">#</th>
			<th scope="col">Header</th>
			<th scope="col">Header</th>
			<th scope="col">Header</th>
			<th scope="col">Header</th>
		</tr>
		</thead>
		<tbody>
		<tr>
			<td>1,001</td>
			<td>random</td>
			<td>data</td>
			<td>placeholder</td>
			<td>text</td>
		</tr>
		<tr>
			<td>1,002</td>
			<td>placeholder</td>
			<td>irrelevant</td>
			<td>visual</td>
			<td>layout</td>
		</tr>
		<tr>
			<td>1,003</td>
			<td>data</td>
			<td>rich</td>
			<td>dashboard</td>
			<td>tabular</td>
		</tr>
		<tr>
			<td>1,003</td>
			<td>information</td>
			<td>placeholder</td>
			<td>illustrative</td>
			<td>data</td>
		</tr>
		<tr>
			<td>1,004</td>
			<td>text</td>
			<td>random</td>
			<td>layout</td>
			<td>dashboard</td>
		</tr>
		<tr>
			<td>1,005</td>
			<td>dashboard</td>
			<td>irrelevant</td>
			<td>text</td>
			<td>placeholder</td>
		</tr>
		<tr>
			<td>1,006</td>
			<td>dashboard</td>
			<td>illustrative</td>
			<td>rich</td>
			<td>data</td>
		</tr>
		<tr>
			<td>1,007</td>
			<td>placeholder</td>
			<td>tabular</td>
			<td>information</td>
			<td>irrelevant</td>
		</tr>
		<tr>
			<td>1,008</td>
			<td>random</td>
			<td>data</td>
			<td>placeholder</td>
			<td>text</td>
		</tr>
		<tr>
			<td>1,009</td>
			<td>placeholder</td>
			<td>irrelevant</td>
			<td>visual</td>
			<td>layout</td>
		</tr>
		<tr>
			<td>1,010</td>
			<td>data</td>
			<td>rich</td>
			<td>dashboard</td>
			<td>tabular</td>
		</tr>
		<tr>
			<td>1,011</td>
			<td>information</td>
			<td>placeholder</td>
			<td>illustrative</td>
			<td>data</td>
		</tr>
		<tr>
			<td>1,012</td>
			<td>text</td>
			<td>placeholder</td>
			<td>layout</td>
			<td>dashboard</td>
		</tr>
		<tr>
			<td>1,013</td>
			<td>dashboard</td>
			<td>irrelevant</td>
			<td>text</td>
			<td>visual</td>
		</tr>
		<tr>
			<td>1,014</td>
			<td>dashboard</td>
			<td>illustrative</td>
			<td>rich</td>
			<td>data</td>
		</tr>
		<tr>
			<td>1,015</td>
			<td>random</td>
			<td>tabular</td>
			<td>information</td>
			<td>text</td>
		</tr>
		</tbody>
	</table>
</div>

<style>

</style>
