<template>
    
    <v-card class="mx-auto" elevation="24">

      <v-carousel hide-delimiters>
          <v-carousel-item src="/ivan-stern-LOLSb7m6XkU-unsplash.jpg" cover> </v-carousel-item>
          <v-carousel-item src="/jay-wennington-N_Y88TWmGwA-unsplash.jpg" cover> </v-carousel-item>
          <v-carousel-item src="../public/patrick-tomasso-GXXYkSwndP4-unsplash.jpg" cover> </v-carousel-item>
          <v-carousel-item src="https://cdn.vuetifyjs.com/images/cards/docks.jpg" cover> </v-carousel-item>
      </v-carousel>

    </v-card>
    
    <v-container>
        <v-card class="mx-auto" elevation="24">
            <v-container>
            <v-row>
                <v-col cols="12" md="4">
                    <v-card>
                        <v-card color="teal-darken-4">
                            <v-card-item>
                                <v-card-title>Special delicacies!</v-card-title>

                                <v-card-subtitle>Chicken korma</v-card-subtitle>
                            </v-card-item>
                            <v-img height="300px" src="../public/Chicken Korma.jpg" cover ></v-img>

                            <v-card-text>
                              Creamy mild coconut chicken curry served with steamed vegetables and mango chutney. With your choice of rice, fries or mashed potatoes.
                            </v-card-text>
                        </v-card>
                        <v-card color="teal-darken-4">
                            <v-card-item>

                            <v-card-subtitle>Nyama Feast Pizza</v-card-subtitle>
                            </v-card-item>
                            <v-img height="400px" src="../public/pexels-enginakyurt-2619970.jpg" cover ></v-img>

                            <v-card-text>
                              Beef Sausages, beef strips, chicken cubes, tomato and mozzarella cheese 
                            </v-card-text>
                        </v-card>
                    </v-card>

                </v-col>

                <v-col cols="12" md="4">
                    <v-card>
                    <v-card color="teal-darken-4">
                    <v-card-item>
                    <v-card-title>Upcoming Events</v-card-title>

                    <v-card-subtitle>Karaoke night!</v-card-subtitle>
                    </v-card-item>
                    <v-img height="300px" src="../public/karaoke night.jpg" cover ></v-img>

                    <v-card-text>
                    Get ready to belt out your favorite tunes at our upcoming Karaoke Night! Join us for an evening of fun, laughter, and musical mayhem as we take the stage to sing our hearts out!
                    </v-card-text>
                    </v-card>
                    <v-card color="teal-darken-4">
                    <v-card-item>
                    
                      <v-card-subtitle>Mini-concert</v-card-subtitle>
                    </v-card-item>
                    <v-img height="400px" src="../public/njerae concert.jpg" cover ></v-img>

                    <v-card-text>
                      Join us for an intimate evening of live music featuring Njerae 🤩, performing a selection of her most beloved hits in a cozy, relaxed setting at Kwetu Dines!
                    </v-card-text>
                    </v-card>
                </v-card>

                </v-col>

                <v-col cols="12" md="4">
                    <v-card>
                        <v-card color="teal-darken-4">
                    <v-card-item>
                    <v-card-title>Promotions</v-card-title>

                    <v-card-subtitle>Hawaiian Barbeque Burger</v-card-subtitle>
                    </v-card-item>
                    <v-img height="300px" src="../public/jonathan-borba-8l8Yl2ruUsg-unsplash.jpg" cover ></v-img>

                    <v-card-text>
                      Chicken Breast/Beef Patty with Beef Macon, grilled pineapple, fresh onion rings, tomatoes, shredded lettuce, melted cheese, Hawaiian BBQ sauce with ranch dressing.
                    </v-card-text>
                        </v-card>
                        <v-card color="teal-darken-4">
                    <v-card-item>
                    <v-card-subtitle>Banana split Milkshake</v-card-subtitle>
                    </v-card-item>
                    <v-img height="400px" src="../public/Ultimate Banana Split Milkshakes Recipe Guide.jpg" cover ></v-img>

                    <v-card-text>
                      A luscious blend of ripe bananas, velvety vanilla ice cream, and creamy milk, swirled together for the perfect thick and smooth shake!
                    </v-card-text>
                        </v-card>
                    </v-card>

                </v-col>
            </v-row>
        </v-container>
        </v-card>
    </v-container>

    <v-container>
        <v-card class="mx-auto" elevation="24" color = "teal-accent-3">
            <v-container>
                <v-row >
                    <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                                <v-card-title>Contact Us</v-card-title>
                            </v-card-item>
                            <v-card-text><v-icon icon="mdi-phone" /> 0722123456</v-card-text>
                            <v-card-text><v-icon icon="mdi-email" /> myrestaurant@example.com</v-card-text>
                            <v-card-text>Operating Hours: 10.00am - 10.00pm</v-card-text>
                        </v-card>
                    </v-col>

                        <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                            <v-card-title>Find us on our socials</v-card-title>

                            </v-card-item>
                            <v-card-text><v-icon icon="mdi-instagram" /> myrestaurant</v-card-text>
                            <v-card-text><v-icon icon="mdi-twitter" /> myrestaurant</v-card-text>
                            <v-card-text><v-icon icon="mdi-facebook" /> myrestaurant</v-card-text>
                        </v-card>
                    </v-col>
                    <v-col cols="12" md="4">
                        <v-card>
                            <v-card-item>
                            <v-card-title>Our Restaurant Locations</v-card-title>
                            </v-card-item>
                            <v-card-text>Madaraka</v-card-text>
                            <v-card-text>CBD</v-card-text>
                            <v-card-text>Langata</v-card-text>
                        </v-card>
                    </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>

  </template>
  
  <script setup>
  </script>
  