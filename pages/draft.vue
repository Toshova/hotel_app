<template>
  <div id="chart">
    <apexchart type="bar" height="300" :options="chartOptions" :series="series"></apexchart>

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
            data: [35, 21,17,15, 13,10, 8, 7,5,4]
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

            dataLabels: {
              enabled: false,
          },
          colors: ['#0066FF'],
              grid: {
                show: false
              },
             
            tooltip: {
              trigger: 'item',
              axisPointer: { type: 'cross', crossStyle: { type: 'solid' } },
              fixed: {
                enabled: false,
              },
              custom: function({ series, seriesIndex, dataPointIndex, w }) {
                
                if (dataPointIndex<10){
                  return (
                    '<div id="tooltip_right" class="tooltip_right">' +
                      '<span class="tooltip_right xxxs_font">' +
                      series[seriesIndex][dataPointIndex]+ ' % ' + '<br />' + 'Инос - 120 чел' + '<br />' + 'Узб - 70 чел'+
                      "</span>" +
                      "</div>"
                  );
                } else {
                  return (
                    '<div id="tooltip_left" class="tooltip_left">' +
                      '<span class="tooltip_left xxxs_font">' +
                      series[seriesIndex][dataPointIndex] + ' % ' + '<br />' + 'Инос - 120 чел' + '<br />' + 'Узб - 70 чел'+
                      "</span>" +
                      "</div>"
                  );
                }
                  
            }
          },

            xaxis: {
                axisBorder: {
                     show: false
                    },
                axisTicks: { 
                    show: false
                 },
                 labels:{
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
              axisTicks: {
                show: true
              }
            }
            
          }
          

      }
        
      }
    }
  
  
  </script>
  
  
  <style>
.apexcharts-bar-series.apexcharts-plot-series  .apexcharts-series path {
    clip-path: inset(0px 0% 0% 0% round 6px);
}

  </style>
  