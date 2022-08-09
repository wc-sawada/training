<script>
import { Bar } from 'vue-chartjs';

export default {
  extends: Bar,
  name: 'chart',
  data () {
    return {
      data: {
        labels: ['フロントエンド', 'バックエンド', 'インフラ(ネットワーク)', 'デザイナー'],
        datasets: [
          {
            label: '平均年収',
            data: [443, 463, 455,411],
            backgroundColor: [
              'rgba(186, 255, 254, 1)',
              'rgba(127, 203, 247, 1)',
              'rgba(186, 255, 254, 1)',
              'rgba(186, 255, 254, 1)',
              ],
          },
        ]
      },
      options: {
        responsive: true,
        maintainAspectRatio: false,
        scales: {
          xAxes: [{
            categoryPercentage: 0.4,
            barPercentage: 0.9,
            scaleLabel: {
              display: true,
              labelString: 'Works'
            }
          }],
          yAxes: [{
            ticks: {
              beginAtZero: false,
              stepSize: 20,
            }
          }]
        }
      },
    }
  },
  mounted () {
    this.renderChart(this.data, this.options)
  }
}
</script>