<template lang="html">
  <section class="chartjs">
    <!-- ACÁ PUEDE SERVIR PARA LA AGENDA NO BORRAR -->
    
    <div class='row' >
      <div class='col-md-4 grid-margin stretch-card'>
        <div class='card' >
          <div class='card-body'>
            <h4 class='card-title mb-0'>Recent Event</h4>
            <div class='d-flex py-2 border-bottom'>
              <div class='wrapper'>
                <small class='text-muted'>Mar 14, 2019</small>
                <p class='font-weight-semibold text-gray mb-0'>Change in Directors</p>
              </div>
              <small class='text-muted ml-auto'>Edit event</small>
            </div>
            <div class='d-flex py-2 border-bottom'>
              <div class='wrapper'>
                <small class='text-muted'>Mar 14, 2019</small>
                <p class='font-weight-semibold text-gray mb-0'>Other Events</p>
              </div>
              <small class='text-muted ml-auto'>Edit event</small>
            </div>
            <div class='d-flex py-2 border-bottom'>
              <div class='wrapper'>
                <small class='text-muted'>Mar 14, 2019</small>
                <p class='font-weight-semibold text-gray mb-0'>Quarterly Report</p>
              </div>
              <small class='text-muted ml-auto'>Edit event</small>
            </div>
            <div class='d-flex pt-2'>
              <div class='wrapper'>
                <small class='text-muted'>Mar 14, 2019</small>
                <p class='font-weight-semibold text-gray mb-0'>Change in Directors</p>
              </div>
              <small class='text-muted ml-auto'>Edit event</small>
            </div>
            <a class='d-block mt-5' href='#'>Show all</a>
          </div>
        </div>
      </div>
      <div class='col-md-4 grid-margin stretch-card'>
        <div class='card'>
          <div class='card-body'>
            <div class='d-flex justify-content-between pb-3'>
              <h4 class='card-title mb-0'>Activities</h4>
              <p class='mb-0 text-muted'>20 finished, 5 remaining</p>
            </div>
            <ul class='timeline'>
              <li class='timeline-item'>
                <p class='timeline-content'><a href='#'>Ben Tossell</a> assign you a task</p>
                <p class='event-time'>Just now</p>
              </li>
              <li class='timeline-item'>
                <p class='timeline-content'><a href='#'>Ben Tossell</a> assign you a task</p>
                <p class='event-time'>Just now</p>
              </li>
              <li class='timeline-item'>
                <p class='timeline-content'><a href='#'>Ben Tossell</a> assign you a task</p>
                <p class='event-time'>Just now</p>
              </li>
              <li class='timeline-item'>
                <p class='timeline-content'><a href='#'>Ben Tossell</a> assign you a task</p>
                <p class='event-time'>Just now</p>
              </li>
              <li class='timeline-item'>
                <p class='timeline-content'><a href='#'>Ben Tossell</a> assign you a task</p>
                <p class='event-time'>Just now</p>
              </li>
            </ul>
            <a class='d-block mt-3' href='#'>Show all</a>
          </div>
        </div>
      </div>

      
      <div class="container">
  <div class="row">
    <div class="col-md-12 grid-margin">
      <table class="table table-bordered">
        <thead>
          <tr>
            <th scope="col">Select Day</th>
            <th scope="col">Article Name</th>
            <th scope="col">Author</th>
            <th scope="col">Words</th>
            <th scope="col">Shares</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>
              <div class="custom-control custom-checkbox">
                  <input type="checkbox" class="custom-control-input" id="customCheck1" checked>
                  <label class="custom-control-label" for="customCheck1">1</label>
              </div>
            </td>
            <td>Bootstrap 4 CDN and Starter Template</td>
            <td>Cristina</td>
            <td>913</td>
            <td>2.846</td>
          </tr>
          <tr>
            <td>
              <div class="custom-control custom-checkbox">
                  <input type="checkbox" class="custom-control-input" id="customCheck2">
                  <label class="custom-control-label" for="customCheck2">2</label>
              </div>
            </td>
            <td>Bootstrap Grid 4 Tutorial and Examples</td>
            <td>Cristina</td>
            <td>1.434</td>
            <td>3.417</td>
          </tr>
          <tr>
            <td>
              <div class="custom-control custom-checkbox">
                  <input type="checkbox" class="custom-control-input" id="customCheck3">
                  <label class="custom-control-label" for="customCheck3">3</label>
              </div>
            </td>
            <td>Bootstrap Flexbox Tutorial and Examples</td>
            <td>Cristina</td>
            <td>1.877</td>
            <td>1.234</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
      
     

  <!--Card image-->
  
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
