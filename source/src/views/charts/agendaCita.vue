<template lang="html">
  <section class="chartjs">
    <!-- ACÁ PUEDE SERVIR PARA LA AGENDA NO BORRAR -->
    
    <div class='row' >
     <table class="table table-striped table-hover table-bordered">
                <thead>
                    <tr>
                        <th>#</th>
                        <th>Paciente <i class="fa fa-sort"></i></th>
                        <th>Fecha</th>
                        <th>Hora <i class="fa fa-sort"></i></th>
                        <th>Numero de documento</th>
                        <th>Acción</th>
                        
                        
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Thomas Hardy</td>
                        <td>Acá va la fecha jeje</td>
                        <td>La hora no se aun</td>
                        <td>97219</td>
                        <td>
                            <button type="submit" class="btn btn-primary">Posponer</button>
                                                        
                        </td>                      
                        
                        
                    </tr>
                           
                </tbody>
            </table>
            <div class="clearfix">
                <div class="hint-text">Página <b>1</b> de <b>1</b></div>
                <ul class="pagination">
                    <li class="page-item disabled"><a href="#"><i class="fa fa-angle-double-left"></i></a></li>
                    <li class="page-item active"><a href="#" class="page-link">1</a></li>
                    
                    <li class="page-item"><a href="#" class="page-link"><i class="fa fa-angle-double-right"></i></a></li>
                </ul>
            </div>    
    </div>

    
  </section>
  
</template>

<script lang="js">
import lineChart from '../../components/charts/examples/lineChart'
import barChart from '../../components/charts/examples/barChart'
import areaChart from '../../components/charts/examples/areaChart'
import doughnutChart from '../../components/charts/examples/DoughnutChart'
import pieChart from '../../components/charts/examples/pieChart'
import scatterChart from '../../components/charts/examples/scatterChart'
export default {
  name: 'chartjs',
  components: {
    lineChart,
    barChart,
    areaChart,
    doughnutChart,
    pieChart,
    scatterChart
  }
}
</script>

<style scoped lang="scss">
  .chartjs {}
</style>
