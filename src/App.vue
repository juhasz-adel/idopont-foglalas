<template>
<div class="container">
  <div class="row">
    <div class="col-md-12">
      <div class="box">
        <h1>Időpont foglalás</h1>
        <form>
          <div class="row">
            <div class="col-6">
              <div class="form-group">
                <label>Vezetéknév</label>
                <input type="text" class="form-control" placeholder="Írja be a vezetéknevét">
              </div>

            </div>
            <div class="col-6">
              <div class="form-group">
                <label>Keresztnév</label>
                <input type="text" class="form-control" placeholder="Írja be a keresztnevét">
              </div>
              
            </div>
            <div class="col-6">
              <div class="form-group">
                <label>Telefonszám</label>
                <input type="text" class="form-control" placeholder="Adja meg a telefonszámát">
              </div>
              
            </div>
            <div class="col-6">
              <div class="form-group">
                <label>Email</label>
                <input type="email" class="form-control" placeholder="Adja meg email címét">
              </div>
              
            </div>
            <div class="col-6">
              <div class="form-group">
                <label>Választott szolgáltatás</label>
                <select name="" class="form-control">
                  <option>Válasszon szolgáltatást</option>
                  <option>Szemöldökszedés</option>
                  <option>Arckezelés</option>
                  <option>Gyantázás</option>
                </select>
              </div>
            </div>
            <div class="col-6">
              <div class="form-check">

                <label class="form-check-label" for="sex">Férfi</label>
                <input class="form-check-input" name="sex" id="sex" type="radio">
            </div>
              <div class="form-check">

                <label class="form-check-label" for="sex2">Nő</label>
                <input class="form-check-input" name="sex" id="sex2" type="radio">
            </div>
            </div>
            <div class="col-6">
              <div class="form-group">
                <label for="">Időpont választása</label>
                <input class="form-control" type="date" name="" id="">
                
              </div>
            </div>
            <div class="col-12">
              <div class="form-group">
                <label for="">
                Megjegyzés
              </label>
              <textarea class="form-control" name="" id="" cols="30" rows="10"></textarea>
              </div>
            </div>
            <div class="col-12">
              <div class="form-group">
                <input class="form-check-input" type="checkbox" name="" id="aszf">
                <label class="form-check-label" for="aszf">Elfogadom az általános szerződéses feltételeket</label>
              </div>
            </div>
            <div class="col-6">
              <input class="btn btn-primary btn-lg" type="button" value="Időpont foglalás">
            </div>
          </div>
        </form>
      </div>
      </div>
  </div>
</div>

 
</template>




