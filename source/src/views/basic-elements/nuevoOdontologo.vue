<template lang="html">

  <section class="typography">
        <div class="card">
          <div class="card-body"><hr size="30" />
            <center><h4 class='card-title mb-0'>REGISTRO NUEVO ODONTÓLOGO</h4></center>
            <hr size="30" />
            <form>
              
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Nombres: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="Nombres">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Apellidos: </label>
      <input type="text" class="form-control" id="text" placeholder="Apellidos">
    </div>

  </div>
   <div class="form-row">
  <div class="form-group col-md-6">
  <label for="text">Fecha de Nacimiento:</label>

<input type="date" id="text" name="trip-start"
       value="2018-07-22"
       min="1900-01-01" max="2020-12-31">
  </div>
  
  <div class="form-group col-md-6">
    <label for="text">Género:</label> <br>
  <input type="radio" name="optradio" checked> Masculino</label>
<input type="radio" name="optradio"> Femenino</label>
</div>
<div class="form-group col-md-6">
    <label for="inputAddress">Dirección de atención: </label>
    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
  </div>
  <div class="form-group col-md-6">
      <label for="inputEmail4">Teléfono: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="3126666666">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Correo Electrónico: </label>
      <input type="text" class="form-control" id="text" placeholder="ejemplo@.....">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Numero de documento: </label>
      <input type="text" class="form-control" id="text" placeholder="1234567890">
    </div>
  </div>
<div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Teléfono: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="3126666666">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Correo Electrónico: </label>
      <input type="text" class="form-control" id="text" placeholder="ejemplo@.....">
    </div>
  </div>
<div class="form-row">
       <div class="form-group col-md-6">
      <label for="inputEmail4">Celular: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="3229566477">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Numero de registro: </label>
      <input type="text" class="form-control" id="text" placeholder="1234567890">
    </div>
 
  <div class="form-group col-md-6">
      <label for="inputEmail4">Contraseña: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="********">
    </div>
     </div>
</form>   
          </div>
        </div>
      </div>
          </div>
            </div>
           
          </div>
        </div>
      </div>
      <button type="submit" class="btn btn-primary">Guardar</button>
 
    </div>
  </section>

</template>

<script lang="js">
export default {
  name: 'typography'
}
</script>

<style scoped lang="scss">
.typography {
}
</style>
