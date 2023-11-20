<template>
  <h1 class="mt-8 ms-7">Edition Hotel - La Badira Hammamet</h1>
  <div class="container top-0 position-sticky z-index-sticky mt-5">
    <div class="row">
      <div class="col-12">
        <navintf
          isBlur="blur  border-radius-lg my-3 py-2 start-0 end-0 mx-4 shadow"
          v-bind:darkMode="true"
          isBtn="bg-gradient-success"
        />
      </div>
    </div>
    <h2 class="mt-8 mx-5">Accomodations :</h2>
    <div class="card mt-3 mx-5">
      <div class="p-3 pb-0 card-header">
        <h5>Hebergements Standard :</h5>
        <table class="table table-striped">
          <thead>
            <tr>
              <th scope="col">#</th>
              <th scope="col">Type de chamber</th>
              <th scope="col">Capacite audilte</th>
              <th scope="col">Description</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <td>Chamber Single</td>
              <td>
                <select v-model="selected">
                  <option disabled value="">Choisissez</option>
                  <option>TRUE</option>
                  <option>FALSE</option>
                </select>
              </td>
              <td><argon-input type="text" placeholder="Description" /></td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <td>Chamber Double</td>
              <td>
                <select v-model="selected">
                  <option disabled value="">Choisissez</option>
                  <option>TRUE</option>
                  <option>FALSE</option>
                </select>
              </td>
              <td><argon-input type="text" placeholder="Description" /></td>
            </tr>
            <tr>
              <th scope="row">3</th>
              <td>Chamber Triple</td>
              <td>
                <select v-model="selected">
                  <option disabled value="">Choisissez</option>
                  <option>TRUE</option>
                  <option>FALSE</option>
                </select>
              </td>
              <td><argon-input type="text" placeholder="Description" /></td>
            </tr>
            <tr>
              <th scope="row">4</th>
              <td>Chamber Quadruple</td>
              <td>
                <select v-model="selected">
                  <option disabled value="">Choisissez</option>
                  <option>TRUE</option>
                  <option>FALSE</option>
                </select>
              </td>
              <td><argon-input type="text" placeholder="Description" /></td>
            </tr>
            <tr>
              <th scope="row">5</th>
              <td>Chamber Mobilite Reduite</td>
              <td>
                <select v-model="selected">
                  <option disabled value="">Choisissez</option>
                  <option>TRUE</option>
                  <option>FALSE</option>
                </select>
              </td>
              <td><argon-input type="text" placeholder="Description" /></td>
            </tr>
          </tbody>
        </table>
        <h5>Capacite :</h5>
        <table class="table table-striped">
          <thead>
            <tr>
              <th scope="col">#</th>
              <th scope="col">Type de chamber</th>
              <th scope="col">Capacite audilte</th>
              <th scope="col">Pax min</th>
              <th scope="col">Pax max</th>
              <th scope="col">Capacite audilte</th>
              <th scope="col">Pax min</th>
              <th scope="col">Pax max</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <td>Chamber Single</td>
              <td>1</td>
              <td>1</td>
              <td>1</td>
              <td>0</td>
              <td>0</td>
              <td>0</td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <td>Chamber Double</td>
              <td>2</td>
              <td>1</td>
              <td>2</td>
              <td>0</td>
              <td>0</td>
              <td>0</td>
            </tr>
            <tr>
              <th scope="row">3</th>
              <td>Chamber Triple</td>
              <td>3</td>
              <td>1</td>
              <td>3</td>
              <td>0</td>
              <td>0</td>
              <td>0</td>
            </tr>
            <tr>
              <th scope="row">4</th>
              <td>Chamber Quadruple</td>
              <td>4</td>
              <td>1</td>
              <td>4</td>
              <td>0</td>
              <td>0</td>
              <td>0</td>
            </tr>
            <tr>
              <th scope="row">5</th>
              <td>Chamber Mobilite Reduite</td>
              <td>1</td>
              <td>1</td>
              <td>2</td>
              <td>0</td>
              <td>0</td>
              <td>0</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="pt-6"></div>
  <div class="card mt-3 mx-6">
    <div class="p-3 pb-0 card-header">
      <h5>Hebergements Spécifiques :</h5>
      <table class="table table-striped">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Type de chamber</th>
            <th scope="col">Capacite audilte</th>
            <th scope="col">Description</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">6</th>
            <td>Suite Fell</td>
            <td>
              <select v-model="selected">
                <option disabled value="">Choisissez</option>
                <option>TRUE</option>
                <option>FALSE</option>
              </select>
            </td>
            <td><argon-input type="number" placeholder="capacite" /></td>
          </tr>
          <tr>
            <th scope="row">7</th>
            <td>Suite Jasmin</td>
            <td>
              <select v-model="selected">
                <option disabled value="">Choisissez</option>
                <option>TRUE</option>
                <option>FALSE</option>
              </select>
            </td>
            <td><argon-input type="number" placeholder="capacite" /></td>
          </tr>
          <tr>
            <th scope="row">8</th>
            <td>Double Bungalow</td>
            <td>
              <select v-model="selected">
                <option disabled value="">Choisissez</option>
                <option>TRUE</option>
                <option>FALSE</option>
              </select>
            </td>
            <td><argon-input type="number" placeholder="capacite" /></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <div class="pt-6"></div>
  <div class="card mt-3 mx-6">
    <div class="p-3 pb-0 card-header">
      <h5>Nouveau Type De Chamber :</h5>
      <div class="row">
        <div class="col">Nom :</div>
        <div class="col">
          <argon-input type="Text" placeholder="Nom" />
        </div>
        <div class="col">
          <select v-model="selected">
            <option disabled value="">Choisissez</option>
            <option>TRUE</option>
            <option>FALSE</option>
          </select>
        </div>
        <div class="col">
          <argon-button color="success" size="md" variant="gradient"
            >AJOUTER</argon-button
          >
        </div>
      </div>
    </div>
  </div>

  <div class="pt-6"></div>
</template>

<script>
import navintf from "@/examples/PageLayout/NavItrf";
import ArgonInput from "@/components/ArgonInput.vue";
//import ArgonSwitch from "@/components/ArgonSwitch.vue";
import ArgonButton from "@/components/ArgonButton.vue";

export default {
  name: "InterfOne",
  components: {
    navintf,
    ArgonInput,
    //ArgonSwitch,
    ArgonButton,
  },
  created() {
    this.$store.state.showFooter = false;
  },
};
</script>
