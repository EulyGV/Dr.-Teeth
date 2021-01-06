<template lang="html">

  <section class="typography">
    <div class="row">
      <div class="col-md-7 grid-margin stretch-card">
        <div class="card">
          <div class="card-body"><hr size="30" />
            <center><h4 class='card-title mb-0'>REGISTRO HISTORIA CLINICA</h4></center>
            <hr size="30" />
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
  <label for="text">Fecha de Nacimiento:</label>

<input type="date" id="text" name="trip-start"
       value="2018-07-22"
       min="1900-01-01" max="2020-12-31">
  </div>
  
  <div class="form-group col-md-6">
    <label for="text">Género:</label> <br>
  <input type="radio" name="optradio" checked>Masculino</label>
<input type="radio" name="optradio">Femenino</label>
</div>
  </div>
  <div class="form-group">
    <label for="inputAddress">Dirección de residencia: </label>
    <input type="text" class="form-control" id="inputAddress" placeholder="1234 Main St">
  </div>

  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputCity">Nacionalidad: </label> <br>
     <select id="inputState" class="form-control">
        <option selected>Choose...</option>
        <option>...</option>
      </select>
    </div>
    <div class="form-group col-md-6">
      <label for="inputState">Ciudad</label>
      <select id="inputState" class="form-control">
        <option selected>Choose...</option>
        <option>...</option>
      </select>
    </div>
    
  </div>
<div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Telefono: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="12321321">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Correo Electronico: </label>
      <input type="text" class="form-control" id="text" placeholder="ejemplo@.....">
    </div>

  </div>

<div class="form-row">
   
    <div class="form-group col-md-6">
      <label for="inputState">Tipo de documento: </label>
      <select id="inputState" class="form-control">
        <option selected>Choose...</option>
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

  <div class="form-group">
    <label for="inputAddress">Eps: </label>
    <input type="text" class="form-control" id="inputEps" placeholder="Eps">
  </div>
    
 
</form>
            

  
          </div>
        </div>
      </div>
      
    <div class="col-md-5 grid-margin">
        <div class="card">
          <div class="card-body">
            <br>
           <div class="card-body"><hr size="30" />
            <center><h4 class='card-title mb-0'>INFORMACIÓN GENERAL</h4></center>
            <hr size="30" />
            <form>
  <div class="form-row">
    <div class="form-group col-md-6">
      <label for="inputEmail4">Nombre Odontólogo: </label>
      <input type="email" class="form-control" id="inputEmail4" placeholder="Nombre">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Apellidos Odontólogo: </label>
      <input type="text" class="form-control" id="text" placeholder="Apellidos">
    </div>

<div class="form-row">
  <div class="form-group col-md-12">
  <label for="text">Fecha Elaboración:</label>
<br>
<input type="date" id="text" name="trip-start"
       value="2018-07-22"
       min="1900-01-01" max="2020-12-31">
  </div>
  </div>
  
  </div>
   </form>
   </div>
<br><br>
   <div class="card-body"><hr size="30" />
   
            <center><h4 class='card-title mb-0'>INFORMACIÓN ACUDIENTE (Opcional)</h4></center>
            <hr size="30" />
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
    <div class="form-group col-md-6">
      <label for="text">Telefono: </label>
      <input type="text" class="form-control" id="text" placeholder="14235436">
    </div>
    <div class="form-group col-md-6">
      <label for="text">Parentesco: </label>
      <input type="text" class="form-control" id="text" placeholder="Parentesco">
    </div>
    </div>
              
              </form>
</div>
  
          </div>
        </div>
      </div>
          
   
      <div class="col-md-12 grid-margin">
        <div class="card">
          <div class="card-body"><hr size="30" />
            <center><h4 class='card-title mb-0'>ANTECEDENTES PERSONALES</h4></center>
            <hr size="30" />
              <div class="modal-body row">
     <div class="col-md-6">
  <div class="pregunta">1. Tratamiento médico actual<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">2. Toma medicamentos<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">3. Alergias<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">4. Cardiopatías<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">5. Alteración presión arterial<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">6. Embarazo<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   <div class="pregunta">7. Diabetes<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  </div>
  <div class="col-md-6">
   <div class="pregunta">8. Hépatitis<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
   
   <div class="pregunta">9. Discrasias Sanguíneas<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  <div class="pregunta">10. Enfermedades Renales<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  <div class="pregunta">11. Inmunosupresión<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  <div class="pregunta">12. Trastornos Respiratorios<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  <div class="pregunta">13. Enfermedades Orales<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  <div class="pregunta">14. Cirugias<br />
  </div>
  <div class="respuestas">
    <input type="radio" name="preg1" value="1" /> Sí<br />
    <input type="radio" name="preg1" value="2" /> No<br />
    
  </div>
  
</div>

 <div class="col-md-12 grid-margin">
<div class="form-group">
  <br><br>
  
    <label for="inputAddress">OTROS: </label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
  </div>
  </div>
  <br>
 <div class="col-md-12 grid-margin">
<div class="form-group">
    <label for="inputAddress">OBSERVACIONES: </label>
    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
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
