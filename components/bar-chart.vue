<template>
  <div id="chart4">
    <apexchart type="bar" height="310" :options="chartOptions" :series="series"></apexchart>

  </div>
  
  </template>
  
  
  
  
  
  <script>
  import VueApexCharts from 'vue-apexcharts'
  
  export default {
    components: {
      apexchart: VueApexCharts,
    },
    data() {
      return {

        series: [{
            data: [23.3, 14, 11.3, 10, 8.6, 6.6, 5.3, 4.6, 3.3, 2.6]
          }],
          chartOptions: {
            chart: {
              type: 'bar',
              toolbar: {
                show: false
              },
            },
            
            plotOptions: {
              bar: {
                barHeight: '16px',
                columnWidth: '32%',
                borderRadius: 6,
                horizontal: true,
                endingShape: 'rounded',
                startingShape: 'rounded',
                colors: {
                  backgroundBarColors: ['#BFDEFF'],
                  backgroundBarRadius: 6,
                },
              }
            },

            legend: {
              height: 0,
              width:0,
              show: false
            },

            tooltip: {
              enabled: false,
            },

            dataLabels: {
              enabled: false,
          },
          colors: ['#0066FF'],
              grid: {
                show: false,
                padding: {
                  top: -15,
                  right: 30,
                  bottom: 0,
                  left: 20
              },  
              },
            

            xaxis: {
              labels: {
                show: false
              },
                axisBorder: {
                     show: false
                    },
                axisTicks: { 
                    show: false
                 },
                 
              categories: ['1. Казахстан',  '2. Российская Федерация', '3. Таджикистан', '4. Китай',  '5. Турция',  '6. Украина',  '7. Азербайджан', '8. Южная Корея',  '9. Соединённые Штаты Америки', '10. Япония',
              ],
              
            },
            fill: {
              opacity: 1
            },

            yaxis: {
              min: 0,
              max: 100,
              reversed: true,
              labels:{
                show: true,
                minWidth: 200,
                maxWidth: 210, 
                offsetX: 0,
                offsetY: 3, 
              },
                
            },
            
          }
          

      }
        
      }
    }
  
  
  </script>
  
  
  <style>
#chart4 .apexcharts-bar-series.apexcharts-plot-series  .apexcharts-series path {
    clip-path: inset(0px 0% 0% 0% round 6px);
   
}

#chart4 .apexcharts-legend {
  max-height: 0px !important;
  width: 0px;
  margin: 0;
  padding: 0;
}
 
  </style>
  