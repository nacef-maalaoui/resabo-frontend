<template>
  <h1 class="mt-8 ms-7">Creation D'un Code De Redaction</h1>
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
  </div>
  <h2 class="mt-8 mx-5">Filtre par :</h2>
  <div class="card mt-3 mx-5">
    <div class="p-3 pb-0 card-header">
      <div class="row">
        <div class="col">Nom</div>
        <div class="col"><argon-input type="text" placeholder="Nom" /></div>
        <div class="col">Date de sejour</div>
        <div class="col"><argon-input type="date" placeholder="Date" /></div>
      </div>
      <div class="row">
        <div class="col">Date de resa</div>
        <div class="col"><argon-input type="date" placeholder="date" /></div>
        <div class="col">Valeur en Montant</div>
        <div class="col">
          <argon-input type="number" placeholder="Montant" />
        </div>
      </div>
    </div>
  </div>
  <h2 class="mt-6 mx-5">Création :</h2>
  <div class="card mt-3 mx-5 pb-2">
    <div class="p-3 pb-0 card-header">
      <div class="row">
        <div class="col-sm-5">Valeur de la Redaction en DT :</div>
        <div class="col-sm-5">
          <argon-input type="text" placeholder="Valeur de la Redaction en DT" />
        </div>
        <div class="col-sm-2">DT</div>
      </div>
      <div class="row">
        <div class="col-sm-5">Valeur de la Redaction en % :</div>
        <div class="col-sm-5">
          <argon-input type="text" placeholder="Valeur de la Redaction en %" />
        </div>
        <div class="col-sm-2">%</div>
      </div>
      <div class="row">
        <div class="col-sm-2">Valide :</div>
        <div class="col-sm-1"><label>DU</label></div>
        <div class="col-sm-4">
          <argon-input type="date" placeholder="DU" />
        </div>
        <div class="col-sm-1"><label>AU</label></div>
        <div class="col-sm-4"><argon-input type="date" placeholder="AU" /></div>
      </div>
      <div class="row">
        <div class="col-sm-2">Sejour :</div>
        <div class="col-sm-1"><label>DU</label></div>
        <div class="col-sm-4">
          <argon-input type="date" placeholder="DU" />
        </div>
        <div class="col-sm-1"><label>AU</label></div>
        <div class="col-sm-4"><argon-input type="date" placeholder="AU" /></div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm-4"></div>
      <div class="col-sm-2">
        <argon-button color="success" size="md" variant="gradient"
          >VALIDER</argon-button
        >
      </div>
      <div class="col-sm-2">
        <argon-button color="success" size="md" variant="outline"
          >ANUULER</argon-button
        >
      </div>
      <div class="col-sm-4"></div>
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
