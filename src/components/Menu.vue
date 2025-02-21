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
                        <v-card>
                        <v-card color="teal-lighten-3">
                          <v-card-item>
                            
                            <v-card-title>{{ item.name }}</v-card-title>
                            <v-card-text>{{ item.price }}</v-card-text>
                            <v-img height="300px" :src="item.image" cover></v-img><br>
                            <v-card-text>{{ item.description }}</v-card-text> <br>
                            <v-btn color="black" variant="tonal" @click="addToOrder()">Order</v-btn>
                            
                          </v-card-item>
                        </v-card>
                        </v-card>
                      </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>
  </v-card>
  </v-container>

  <v-container>
        <v-card color="lime-darken-3" >
            <v-card-title>
                <div class="text-h6">Current order: {{totalOrderAmount}}</div>
            </v-card-title>
        </v-card>
    </v-container>
    <v-container>
        <v-card class="mx-auto" elevation="24">
            <v-container>
                <v-row>
                    <v-col cols="12" md="4" v-for="item in orderItems" :key=item>
                        <v-card color="yellow">
                            <v-card-item>
                            <v-card-title>{{ item.name }}</v-card-title>

                            <v-card-subtitle>{{ item.description }}</v-card-subtitle>
                            </v-card-item>
                            <v-img height="200px" :src="item.image" cover ></v-img>

                            <v-card-text>{{ item.price }}</v-card-text>
                        </v-card>
                        </v-col>
                </v-row>
            </v-container>
        </v-card>
    </v-container>
  
  </template>
  
  <script setup>
    const menuItems = [
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
    {
        name: "Carribean Jack Chicken",
        price: 1800,
        description: "Marinated chicken on bone Caribbean style, grilled to perfection, served with salsa, plantains, salad, 1000 island dressing and ranchero sauce. With your choice of fries or rice or mashed potatoes.",
        size: "None",
        offers: "None",
        image: "/chicken.jpg"
    },
    {
        name: "Chips",
        price: 200,
        description: "Best chips in town",
        size: "Large",
        offers: "None",
        image: "/chips.jpg"
    },
    {
        name: "Sausage",
        price: 50,
        description: "Best sausages in town",
        size: "None",
        offers: "None",
        image: "/sausage.jpg"
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
        image: "/Buttermilk Pancake.jpg"
    },
    {
        name: "Butternut squash soup",
        price: 550,
        description: "Fresh homemade soup prepared for each day of the week. Accompanied with two bread rolls and butter.",
        size: "None",
        offers: "None",
        image: "/butternut squash soup.jpg"
    },
    
]
var orderItems = [];
var totalOrderAmount = 0;

function calculateTotalAmount (price){
    totalOrderAmount += price;
}

function addToOrder (item){
    orderItems.push(item)
    calculateTotalAmount(item.price)
}


</script>
  