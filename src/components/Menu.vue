<template>
   <v-container>
    <v-card class="mx-auto" elevation="24">
        <v-card color="blue" >
            <v-card-title>
                <div class="text-h3">Our Menu</div>
            </v-card-title>
        </v-card>
    
    <v-container>
        <v-card class="mx-auto" elevation="24" color = "brown-darken-2">
            <v-container>
                <v-row >
                    <v-col cols="12" md="4" v-for="item in menuItems" :key="item">
                        <v-card color="teal-lighten-3">
                          <v-card-item>
                            <v-card-title>{{ item.name }}</v-card-title>
                            <v-card-subtitle>{{ item.description }}</v-card-subtitle>
                            <v-card-text>Price: {{ item.price }}</v-card-text>
                          </v-card-item>
                        </v-card>
                      </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>
  </v-card>
  </v-container>

  </template>
  
  <script setup>
    const menuItems = [
    {
        name: "Chips",
        price: 200,
        description: "Best chips in town",
        size: "Large",
        offers: "None",
        image: "https://unsplash.com/photos/a-basket-of-french-fries-sitting-on-top-of-a-wooden-table-ChXHveqrb28?utm_content=creditShareLink&utm_medium=referral&utm_source=unsplash"
    },
    {
        name: "Sausage",
        price: 50,
        description: "Best sausages in town",
        size: "None",
        offers: "None",
        image: "https://unsplash.com/photos/sausage-on-black-round-pan-cSxpCQrRlo8"
    },
    {
        name: "Chocolate chip muffin",
        price: 300,
        description: "Delicious muffin flavored with chocolate drops.",
        size: "None",
        offers: "None",
        image: "/chocolate chip muffin.jpg"
    },
    {
        name: "Original Buttermilk Pancake",
        price: 900,
        description: "Best buttermilk pancakes in town!",
        size: "None",
        offers: "None",
        image: "/Buttermilk Pancake.png"
    },
    {
        name: "Butternut squash soup",
        price: 550,
        description: "Fresh homemade soup prepared for each day of the week. Accompanied with two bread rolls and butter.",
        size: "None",
        offers: "None",
        image: "/butternut squash soup.jpg"
    },
    {
        name: "Beef Burger",
        price: 1300,
        description: "Perfectly grilled beef patty with grilled onions, fresh tomatoes, mayonnaise and shredded lettuce.",
        size: "None",
        offers: "None",
        image: "/beef burger.jpg"
    },
    {
        name: "Samosas",
        price: 350,
        description: "A pair of chicken or beef or vegetable deep fried stuffed pastry shells.",
        size: "None",
        offers: "None",
        image: "/samosas.jpg"
    },
    {
        name: "Masala chips",
        price: 500,
        description: "Chips tossed with fresh coriander, home made masala sauce made of onions, cumin seeds, curry paste, tomato sauce and fresh cream.",
        size: "None",
        offers: "None",
        image: "/masala chips.jpg"
    },
]
  </script>
  