<template lang="html">

  <section class="registro">
    <div class="row">
      <div class="col-md-12 grid-margin stretch-card">
        <div class="card">
          <div class="card-body">
           <div class="table-title">
                <div class="row">
                    <div class="col-sm-8"><h2>NUEVA CITA</h2></div>
                    
                </div>
            </div>
          <br>
            <form>
               <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Nombre: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="Nombre">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Apellidos: </label>
      <input type="text" class="form-control" id="text" placeholder="Apellidos">
    </div>

  </div>

  <div class="form-row">
   
    <div class="form-group col-md-6">
      <label for="inputState">Tipo de documento: </label>
      <select id="inputState" class="form-control">
        <option selected>Seleccionar...</option>
        <option>Tarjeta de Identidad</option>
        <option>Cédula de Ciudadanía</option>
        <option>Cédula de Extranjería</option>
        
      </select>
    </div>
    <div class="form-group col-md-6">
      <label for="text">Numero de documento: </label>
      <input type="text" class="form-control" id="text" placeholder="1234567890">
    </div>
  </div>

  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="text">Fecha de Cita:</label><br>

      <input type="date" id="text" name="trip-start"
       value="2018-07-22"
       min="1900-01-01" max="2020-12-31">
    </div>

    <div class="form-group col-md-6">
    <form action="../../form-result.php" method="post" target="_blank">
    <label for="text">Hora de Cita:</label><br>
      <input type="time" name="eta">

</form>
</div>

  
 </div>
 
 
  </form>
   
        </div>
        
      </div>
    </div>
    <button type="submit" class="btn btn-primary">Guardar</button>
    </div>
  </section>

</template>

<script lang="js">
export default {
  name: 'registro',
  

}


</script>

<style scoped lang="scss">
.registro {

}
</style>
