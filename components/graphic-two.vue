<template>
    <div id="chart">
      <apexchart type="line" height="310" :options="chartOptions" :series="chartSeries" />
    
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
              type: 'area',
              stacked: false,
              toolbar: false,
              background: '#ffffff',
              height: 360,  
              width: 408,
            },
            xaxis: {
                axisBorder: {
                  show: false
                },
              categories: ['1 Янв', '', '5 Янв', '', '10 Янв', '','15 Янв', '', '25 Янв', '',],
            labels: {
              style: {
                cssClass: 'xaxis-label-two'
              }
            }
            
            }, 
          
            stroke: {
              curve: 'smooth',
              lineCap: 'round',
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
                left: 20,
               
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
                labels: {
                  formatter: (val) => {
                    return val + ' %'
                  },
                  align: 'left'
                }
              },
    
             
              tooltip: {
                custom: function({ series, seriesIndex, dataPointIndex, w }) {
                    if (dataPointIndex<5){
                  return (
                    '<div id="tooltip_right" class="tooltip_right">' +
                      '<span class="tooltip_right xxxs_font">' +
                      series[seriesIndex][dataPointIndex]+ ' % от макс. ' + '<br />' + '18 741 400,00 Сум ' +
                      "</span>" +
                      "</div>"
                  );
                } else {
                  return (
                    '<div id="tooltip_left" class="tooltip_left">' +
                      '<span class="tooltip_left xxxs_font">' +
                      series[seriesIndex][dataPointIndex] + ' % от макс. ' + '<br />' + '18 741 400,00 Сум '+
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
            data: [55, 69, 45, 61, 43, 54, 37, 52, 44, 61,]
            },
            
          ]
        }
      }
    }
    
    </script>
    
    
    <style>
.xaxis-label-two {  
    text-anchor: start;
}
    </style>
    
    