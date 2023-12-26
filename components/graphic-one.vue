<template>
  <div id="chart3">
    <apexchart type="line" height="358" :options="chartOptions" :series="chartSeries" />

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
        chartOptions: {
          chart:{        
            type: 'line',
            stacked: false,
            toolbar: false,
            background: '#ffffff',  
          },
          xaxis: {
            axisBorder: {
               show: false
          },
            categories: ['', 'Январь', '', 'Февраль', '', 'Март', '','Апрель', '', 'Май', '', 'Июнь',
            '', 'Июль', '', 'Август', '', 'Сентябрь', '', 'Октябрь', '', 'Ноябрь', '', 'Декабрь', '',]
     }, 
          
          stroke: {
            curve: 'straight',
            width: [2, 2]
          },
  
          fill: {
            type: [ 'gradient', 'solid'],
            gradient: {
                shadeIntensity: 0,
                type: 'vertical',
                opacityFrom: 0.5,
                opacityTo: 0.1,
                stops: [0, 95, 100]
            }
          },

            grid: {
              borderColor: '#e7e7e7',
              strokeDashArray: 7,
              padding: {
                left: 30,
                top: 10
              }
            },
            markers: {
              size: 0,
              strokeColor: ["#0066FF","transparent"],
              colors: ['white', "transparent"]
				    },
            
            yaxis: {
              tickAmount: 4,
              min: 0,
              max: 100,
              offsetX: 0,
              offsetY: 0,
              labels: {
                formatter: (val) => {
                  return val + ' %'
                },
                align: 'left'
              }
            },
  
            legend: {
              position: 'top',
              horizontalAlign: 'left',
              floating: true,
              offsetY: -12,
              offsetX: 27,
              markers: {
                  width: 24,
                  height: 2,
                  strokeWidth: 0,
                  strokeColor: '#fff',
                  fillColors: undefined,
                  offsetX: -5,
                  offsetY: -2.5,
                  customHTML: undefined,
                  onClick: undefined,     
              },
              itemMargin: {
                  horizontal: 25,
                  vertical: 5
              },
            },
            tooltip: {
              trigger: 'item',
              axisPointer: { type: 'cross', crossStyle: { type: 'solid' } },
              fixed: {
                enabled: false,
              },
              custom: function({ series, seriesIndex, dataPointIndex, w }) {
                
                if (dataPointIndex<12){
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
  
            colors: ["#0066FF", "#FFCC33"],      
      },
      
        chartSeries: [
          {
          name: '2021',
          type: 'area',
          data: [5, 20, 24, 30, 38, 37, 48, 55, 50, 37,43, 60, 81, 79, 87, 90, 87, 80, 85, 87, 80, 67, 37, 60,70],
          },
          {
          name: '2020',
          type: 'line',
          data: [5, 3, 18, 24, 45, 49, 97, 89, 68, 78, 80, 85, 84, 76, 58, 67, 89, 87, 90, 89, 80, 89, 95, 90,90]
          }
        ]
      }
    }
  }
  
  </script>
  
  
  <style>

  #chart3{
    margin-top: 20px;
  }
  #chart{
    cursor: pointer; 
    line-height: 18px;
    font-family: 'SF Pro Display', sans-serif;
  }

  .apexcharts-yaxis-label tspan{
    font-size: 13px;
    font-weight: 600;  
}

  .apexcharts-xaxis-label tspan {  
    font-size: 13px;
    font-weight: 400;
}


  #tooltip_left{
  left: -20px;
  top: -5px;
 }

  .tooltip_left {
    position: relative;
    background: #08162BE0;
    opacity: 0.88;
    border-radius: 8px;
    width: 132px;
    height: 60px;  
  }
  .tooltip_left:after, .tooltip_left:before {
    left: 100%;
    top: 50%;
    border:  transparent solid;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none; 
  }
  
  .tooltip_left:after {
    border-left-color: #08162BE0;
    opacity: 0.93;
    border-width: 10px;
    margin-top: -10px; 
  }

  #tooltip_right{
    right: -10px;
    top: -4px; 
 }

  .tooltip_right {
    position: relative;
    background: #08162BE0;
    opacity: 0.88;
    border-radius: 8px;
    width: 132px;
    height: 60px;  
  }
  .tooltip_right:after, .tooltip_right:before {
    right: 100%;
    top: 50%;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none;
   
  }
  
  .tooltip_right:after {
    border-right-color: #08162BE0;
    opacity: 0.93;
    border-width: 10px;
    margin-top: -10px;
    
  }
  
  #chart .apexcharts-tooltip, #chart3 .apexcharts-tooltip {
    color: #fff;
    overflow: visible !important;
  }
  
  #chart .apexcharts-tooltip span, #chart3 .apexcharts-tooltip span  {
    display: flex;
    align-items: center;
    text-align: left;
    padding-left: 10px;
  }

  .apexcharts-tooltip {
    background: transparent !important;
    border-color: transparent !important;
    box-shadow: none !important;
  }
 
  .xxxs_font{
    font-family: 'SF Pro Display', sans-serif;
    font-weight: 500;
    font-size: 11px;
    line-height: 13px;
   }
  
  .apexcharts-xaxistooltip{
    background: transparent !important;  
    border: none !important;
    color: transparent !important;
    margin-top: 4px;
    padding-bottom: 0;
    font-weight: bold;
}
  .apexcharts-xaxistooltip-bottom:before{
    opacity: 0  
  }
  .apexcharts-xaxistooltip-bottom:after{
    opacity: 0  
  }

  .apexcharts-xcrosshairs {
    stroke-linecap: round;
    stroke-width: 2px;
    stroke-dasharray: 0;
    stroke: #D5D8DD;
    
  }

  #chart3 .apexcharts-legend {
    margin-bottom: 30px;
  }

  </style>
  