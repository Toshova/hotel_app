<template>
  <div id="chart2">
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
            name: 'Свободно',
            data: [44, 55, 41, 67, 22, 43, 21, 49, 41, 67, 22, 43,],
            
          }, {
            name: 'Резиденты',
            data: [13, 23, 20, 8, 13, 27, 33, 12, 15, 21, 14, 15,]
          }, {
            name: 'Иностранцы',
            data: [11, 17, 15, 15, 21, 14, 15, 13, 8, 13, 27, 33,]
          }],
          chartOptions: {
            chart: {
              stackType: '100%',
              type: 'bar',
              stacked: true,
              
              toolbar: {
                show: false
              },
            },
            
            colors: ["#9900FF", "#00CC99", "#0066FF"],
            grid: {
              show: false,
            },

            yaxis:{
              show: false,
            },

            plotOptions:{
              bar: {
                columnWidth: 12,
                borderRadius: 6,
              }
            },
            dataLabels: {
          enabled: false,
        },
            
            legend: {
              position: 'top',
              horizontalAlign: 'left',
              floating: true,
              offsetY: -12,
              offsetX: -5,
              markers: {
                  width: 8,
                  height: 8,
                  radius: 4,
                  offsetX: -5,
                  offsetY: -2,     
              },
              itemMargin: {
                  horizontal: 10,
                  vertical: 15
              },
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
              crosshairs: {
                show: false
              },
              axisBorder: { show: false },
              axisTicks: { show: false },
              categories: ['Янв',  'Фев', 'Мар', 'Апр',  'Май',  'Июн',  'Июл', 'Авг',  'Сен', 'Окт', 'Ноя', 'Дек',
              ],
            },
            fill: {
              opacity: 1
            },
            
          }
          

      }
        
      }
    }
  
  
  </script>
  
  
  <style>

 #chart2 .apexcharts-bar-series.apexcharts-plot-series  .apexcharts-series path {
    clip-path: inset(6px 0% 0% 0% round 6px);
}
#chart2 .apexcharts-tooltip {
    color: #fff;
    overflow: visible !important;
  }
  
  #chart2 .apexcharts-tooltip span {
    display: flex;
    align-items: center;
    text-align: left;
    padding-left: 10px;
  }
.apexcharts-bar:hover {
   border: transparent !important;
   }
  </style>
  