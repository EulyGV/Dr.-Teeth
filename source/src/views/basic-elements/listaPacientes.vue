<template lang="html">

  <section class="buttons">
    <div class="row">
      <div class="col-md-12 grid-margin stretch-card">
        <div class="card">
          <div class="card-body">
          


<div class="container-xl">
    <div class="table-responsive">
        <div class="table-wrapper">
            <div class="table-title">
                <div class="row">
                    <div class="col-sm-8"><h2>Listado de Odontólogo</h2></div>
                    
                </div>
            </div>
            <div class="active-cyan-3 active-cyan-4 mb-4">
                <input class="form-control" type="text" placeholder="Buscar" aria-label="Search">
            </div>
            <table class="table table-striped table-hover table-bordered">
                <thead>
                    <tr>
                        <th>#</th>
                        <th>Nombre Completo <i class="fa fa-sort"></i></th>
                        <th>Dirección</th>
                        <th>Ciudad <i class="fa fa-sort"></i></th>
                        <th>Numero de documento</th>
                        <th>Eliminar</th>
                        <th>Ver</th>
                        
                        
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>1</td>
                        <td>Thomas Hardy</td>
                        <td>89 Chiaroscuro Rd.</td>
                        <td>Bucaramanga</td>
                        <td>97219</td>
                        <td>
                            
                            <router-link class="nav-link" to="/Tratamiento/">
                            <button type="submit" class="btn btn-info" >Tratamiento</button>
                            </router-link>                          
                            
                            
                        </td>
                        <td>
                        <button type="submit" class="btn btn-primary">Ver</button>
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
    </div>  
</div>   

</html>
          </div>
        </div>
      </div>
    </div>
  </section>

</template>

<script lang="js">
export default {
  name: 'buttons'
}
</script>

<style scoped lang="scss">
.buttons {

}
</style>
