<template>
  <h1 class="mt-8 ms-7">Edition Hôtel - La Badira Hammamet</h1>
  <div class="container top-0 position-sticky z-index-sticky mt-5">
    <div class="row">
      <div class="col-12">
        <navintf
          isBlur="blur  border-radius-lg my-3 py-2 start-0 end-0 mx-4 shadow "
          v-bind:darkMode="true"
          isBtn="bg-gradient-success"
        />
      </div>
    </div>
  </div>

  <div class="mt-7">
    <div class="py-4 container-fluid">
      <div class="row">
        <div class="col-lg-12">
          <div class="row"></div>
          <div class="row">
            <div class="col-lg-7 mb-lg">
              <!-- line chart -->
              <div class="card z-index-2">
                <div class="card">
                  <div class="pb-0 card-header mb-0"></div>
                  <div class="p-3 card-body row">
                    <div class="chart col">
                      <h6>Fournisseur :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input type="text" placeholder="Fournisseur" />
                    </div>

                    <div class="chart col">
                      <h6>Hotel :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input type="text" placeholder="Hotel" />
                    </div>

                    <div class="chart col">
                      <h6>Ville :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input type="text" placeholder="Ville" />
                    </div>
                    <div class="chart col">
                      <h6>Number d'etoile :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input type="text" placeholder="Number d'etoile" />
                    </div>
                    <div class="chart col">
                      <h6>Addresse physique :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="text"
                        placeholder="Addresse physique "
                      />
                    </div>
                    <div class="chart col">
                      <h6>Maps :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input type="url" placeholder="Maps " />
                    </div>
                    <div class="chart col">
                      <h6>Telephone Fixe :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="number"
                        placeholder="Telephone Fixe "
                      />
                    </div>
                    <div class="chart col">
                      <h6>Telephone Mobile-Service Commerciale:</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="number"
                        placeholder="Telephone Mobile - Service Commerciale "
                      />
                    </div>
                    <div class="chart col">
                      <h6>Telephone Mobile - Service Financier :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="number"
                        placeholder="Telephone Mobile - Service Financier "
                      />
                    </div>
                    <div class="chart col">
                      <h6>Adresse E-mail -Service Reservation :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="email"
                        placeholder="Adresse E-mail -Service Reservation"
                      />
                    </div>
                    <div class="chart col">
                      <h6>Adresse E-mail -Service Commerciale :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="email"
                        placeholder="Adresse E-mail -Service Commerciale "
                      />
                    </div>
                    <div class="chart col">
                      <h6>Adresse E-mail -Service Financier :</h6>
                      <canvas
                        id="chart-line"
                        class="chart-canvas"
                        height="100%"
                      >
                      </canvas>
                    </div>
                    <div class="col">
                      <argon-input
                        type="email"
                        placeholder="Adresse E-mail -Service Financier"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-4 m-auto">
              <img
                src="../assets/img/hotel.jpg"
                class="img-fluid img-thumbnail rounded-3"
                size="xxl"
                alt=""
              />
            </div>
          </div>
          <div class="row mt-4">
            <div class="col-lg-7 mb-lg-0 mb-4">
              <div class="card">
                <div class="p-3 pb-0 card-header">
                  <div class="row">
                    <div class="col-sm-4">
                      <h6>Localisation :</h6>
                    </div>
                    <div class="col-sm-8">
                      <h6>Ville :</h6>
                      <argon-input type="text" placeholder="Ville" />
                      <h6>Balneaire :</h6>
                      <argon-input type="text" placeholder="Balneaire" />
                      <h6>Palmerai :</h6>
                      <argon-input type="text" placeholder="Palmerai" />
                    </div>
                  </div>
                  <div class="row">
                    <div class="col-sm-6">
                      <h6>Equipement Disponible:</h6>
                    </div>
                    <div class="col-sm-6">
                      <argon-input
                        type="text"
                        placeholder="Equipement Disponible:"
                      />
                    </div>
                    <div class="col-sm-6">
                      <h6>Theme Disponible :</h6>
                    </div>
                    <div class="col-sm-6">
                      <argon-input type="text" placeholder="Theme Disponible" />
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <div class="col-lg-5">
              <div class="card">
                <div class="p-3 pb-0 card-header">
                  <div>
                    <h3>Les Restraction :</h3>
                    <h6>N'accepte pas les celibataires</h6>
                    <h6>Adults only</h6>
                    <h6>N'accepte pas les animaux</h6>
                    <h6>accees au Piscine couverte payante</h6>
                    <h6>accees aux salles de sport payant</h6>
                    <h6>cote bebe payant</h6>
                  </div>
                </div>
              </div>
            </div>
          </div>
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
//import ArgonButton from "@/components/ArgonButton.vue";
//import Card from "@/examples/Cards/Card.vue";
//import GradientLineChart from "@/examples/Charts/GradientLineChart.vue";
//import Carousel from "./components/Carousel.vue";
//import CategoriesCard from "./components/CategoriesCard.vue";

import US from "@/assets/img/icons/flags/US.png";
import DE from "@/assets/img/icons/flags/DE.png";
import GB from "@/assets/img/icons/flags/GB.png";
import BR from "@/assets/img/icons/flags/BR.png";

export default {
  name: "InterfOne",
  components: {
    navintf,
    ArgonInput,
    //ArgonSwitch,
    //ArgonButton,
    //Card,
    //GradientLineChart,
    //Carousel,
    //CategoriesCard,
  },
  created() {
    this.$store.state.showFooter = false;
  },
  data() {
    return {
      stats: {
        money: {
          title: "Today's Money",
          value: "$53,000",
          percentage: "+55%",
          iconClass: "ni ni-money-coins",
          detail: "since yesterday",
          iconBackground: "bg-gradient-primary",
        },
        users: {
          title: "Today's Users",
          value: "2,300",
          percentage: "+3%",
          iconClass: "ni ni-world",
          iconBackground: "bg-gradient-danger",
          detail: "since last week",
        },
        clients: {
          title: "New Clients",
          value: "+3,462",
          percentage: "-2%",
          iconClass: "ni ni-paper-diploma",
          percentageColor: "text-danger",
          iconBackground: "bg-gradient-success",
          detail: "since last quarter",
        },
        sales: {
          title: "Sales",
          value: "$103,430",
          percentage: "+5%",
          iconClass: "ni ni-cart",
          iconBackground: "bg-gradient-warning",
          detail: "than last month",
        },
      },
      sales: {
        us: {
          country: "United States",
          sales: 2500,
          value: "$230,900",
          bounce: "29.9%",
          flag: US,
        },
        germany: {
          country: "Germany",
          sales: "3.900",
          value: "$440,000",
          bounce: "40.22%",
          flag: DE,
        },
        britain: {
          country: "Great Britain",
          sales: "1.400",
          value: "$190,700",
          bounce: "23.44%",
          flag: GB,
        },
        brasil: {
          country: "Brasil",
          sales: "562",
          value: "$143,960",
          bounce: "32.14%",
          flag: BR,
        },
      },
    };
  },
};
</script>
