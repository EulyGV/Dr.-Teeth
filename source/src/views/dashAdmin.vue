<template lang='html'>

  <section class='dashboard'>
    <!-- Page Title Header Starts-->
    
    <div class='row page-title-header'>
      <div class='col-12'>
        <div class='page-header'>
          <h4 class='page-title'>Perfil</h4>
          
        </div>
      </div>
      
    </div>
    <!-- Page Title Header Ends-->    
    <div class='row'>
      <div class='col-md-8 grid-margin stretch-card'>
        <div class='card'>
          <div class='card-body'>
            <h4 class='card-title mb-0'>DATOS PERSONALES ADMIN</h4>
            <hr size="30" />
            <div class='d-flex flex-column flex-lg-row'>
              <!--About section starts-->
<section id="about">    
    <div class="row">
        <div class="col-sm-12">
            <div class="card">
                
                <div class="card-body">
                    <div class="card-block">
                        
                        <div class="row">
                            <div class="col-12 col-md-6 col-lg-4">
                                <ul class="no-list-style">
                                    <li class="mb-2">
                                        <span class="text-bold-500 badge badge-secondary"><a><i class="icon-present font-small-3"></i> Nombre:</a></span>
                                        <br>
                                        <span class="display-block overflow-hidden">Maria Lucia</span>
                                    </li>
                                    <li class="mb-2">
                                        <span class="text-bold-500 badge badge-secondary"><a><i class="mdi mdi-account-card-details"></i> Apellidos:</a></span>
                                        <br>
                                        <span class="display-block overflow-hidden">Gomez Rodriguez</span>
                                    </li>
                                    
                                    <li class="mb-2">
                                        <span class="text-bold-500 small badge badge-secondary"><a><i class="mdi mdi-account"></i> Fecha de nacimiento:</a></span>
                                        <br>
                                        <span class="display-block overflow-hidden"> Enero 23, 1999 </span>
                                    </li>
                                </ul>
                            </div>
                            <div class="col-12 col-md-6 col-lg-4">
                                <ul class="no-list-style">
                                    
                                    <li class="mb-2">
                                        <span class="text-bold-500 badge badge-pill badge-secondary"><a><i class="mdi mdi-account"></i> Celular:</a></span>
                                        <br>
                                        <span class="display-block overflow-hidden"> 3155727704 </span>
                                    </li> 
                                    <li class="mb-2">
                                        <span class="text-bold-500 badge badge-secondary"><a><i class="ft-globe font-small-3"></i> Género:</a></span>
                                        <br>
                                        <span class="display-block overflow-hidden">Femenino</span>
                                    </li>
                                   
                                    
                                    
                                </ul>
                            </div>
                                          <div class="col-12 col-md-6 col-lg-4">
                                <ul class="no-list-style">
                                      
                                     
                                    <li class="mb-2">
                                        <span class="text-bold-500 badge badge-secondary">
                                            <a><i class="ft-user font-small-3"></i> Correo electrónico:</a></span>
                                        <span class="display-block overflow-hidden">malugomezr@hotmail.com</span>
                                    </li>
                                     <li class="mb-2">
                                        <span class="text-bold-500 badge badge-secondary">
                                            <a><i class="ft-user font-small-3"></i> Documento identidad:</a></span>
                                        <span class="display-block overflow-hidden">1324346578</span>
                                    </li>                                
                                    
                                    
                                </ul>
                            </div>
                            
                             

                             
                            
                        </div>
                        
                        
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</section>
              
              
            </div>
            
            
          </div>
        </div>
      </div>
      
      <div class='col-md-4 grid-margin stretch-card' >
        <div class='card'>
          <div class='card-body d-flex flex-column'>
            <div class='wrapper' >
                
              <!-- <router-link to="/" tag="img">
               <img  src="@/assets/images/faces/JM.jpeg"/>
           </router-link>  -->
          <!-- <v-img @click="$router.push('/Home')" class="redirect" src="@/assets/images/faces/JM.jpeg" max-width="140px" max-height="150"></v-img>-->
               <center>
                <a href="url">
                   
                 <img src="@/assets/images/faces/MALU.jpg" width="290" height="300" align="absmiddle"/>
                
                </a> 
                </center>
                <hr />
                <hr/>
                <center>
                                        
                <h1>@MALU</h1>
                <hr />
                <hr/>
                </center>

            
             
            </div> 
            
                      
          </div>
        </div>
      </div>
      
    </div>
    
  </section>
</template>

<script lang='js'>
import statsLineGraph1 from '../components/charts/dashboard_1/stats-line-graph-1'
import statsLineGraph2 from '../components/charts/dashboard_1/stats-line-graph-2'
import statsLineGraph3 from '../components/charts/dashboard_1/stats-line-graph-3'
import statsLineGraph4 from '../components/charts/dashboard_1/stats-line-graph-4'
import salesStatisticsOverview from '../components/charts/dashboard_1/sales-statistics-overview'
import netProfit from '../components/charts/dashboard_1/net-Profit'
import totalRevenue from '../components/charts/dashboard_1/total-revenue'
import marketOverviewChart from '../components/charts/dashboard_1/market-overview-chart'
import totalTransaction from '../components/charts/dashboard_1/total-transaction'
import realtimeStatistics from '../components/charts/dashboard_1/realtime-statistics'
import usersDoughnutChart from '../components/charts/dashboard_1/usersDoughnutChart'
import JQuery from 'jquery'
let $ = JQuery
export default {
  name: 'dashboard',
  components: {
    statsLineGraph1,
    statsLineGraph2,
    statsLineGraph3,
    statsLineGraph4,
    salesStatisticsOverview,
    netProfit,
    totalRevenue,
    marketOverviewChart,
    totalTransaction,
    realtimeStatistics,
    usersDoughnutChart
  },
  methods: {
    toggleProBanner: function () {
      $('body').toggleClass('pro-banner-collapse')
    }
  }
}
</script>

<style scoped lang='scss'>
</style>
