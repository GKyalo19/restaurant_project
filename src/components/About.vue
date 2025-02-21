<template>
  <div :style="backgroundStyle">
    <v-container>
      <v-card class="mx-auto text-white centered-card" elevation="24">
        
        <v-card-title class="text-h3">About Us</v-card-title>
        <v-card-text>Welcome to Kwetu, where every meal feels like home! <br><br>
                     At Kwetu, we believe that food is more than just nourishment—it’s a story, a memory, 
                     and a connection to our roots. Inspired by the rich and diverse flavors of African cuisine, 
                     we take pride in bringing you a blend of traditional recipes and modern twists, crafted with 
                     fresh, locally sourced ingredients.
                     Our journey began with a simple yet powerful vision: to create a space where people could 
                     come together and experience the warmth of home-cooked meals, no matter where they are.  
                     Whether you grew up savoring the rich aromas of nyama choma, the comforting texture of ugali,  
                     or the refreshing zest of a perfectly brewed dawa, we aim to bring those flavors to your 
                     table—just the way you remember them.
                     But Kwetu is more than just a restaurant. It’s a celebration of culture, heritage, and 
                     community. Our recipes are inspired by the diverse culinary traditions from across Africa,                      
                     from the spicy stews of West Africa to the coastal delights of East Africa. Every dish tells <br>
                     a story, every spice carries a history, and every bite is a journey through the rich flavors 
                     of our homeland.
        </v-card-text>
      </v-card>
      
    </v-container>
  </div>
</template>

<style scoped>

.centered-card {
  background-color: rgba(0, 0, 0, 0.6); 
  padding: 20px;
  border-radius: 10px;
  width: 50%; 
  text-align: left;
  font-size: 12px;
}

</style>

<script setup>
import backgroundImage from '/ivan-stern-LOLSb7m6XkU-unsplash.jpg';

const backgroundStyle = {
  backgroundImage: `url(${backgroundImage})`,
  backgroundSize: 'cover',
  backgroundPosition: 'center',
  backgroundRepeat: 'no-repeat',
  height: '100vh',
  width: '100vw',
  position: 'fixed',
  top: '0',
  left: '0',
  display: 'flex',
  justifyContent: 'center',
  alignItems: 'center',
};

</script>


<!-- <template>
  <div :style="backgroundStyle">
    <v-container>
      <v-card class="mx-auto text-white centered-card" elevation="24">
        
        <v-card-title class="text-h3">About Us</v-card-title>
        <v-card-text>Welcome to Kwetu, where every meal feels like home! <br><br>
                     At Kwetu, we believe that food is more than just nourishment—it’s a story, a memory, 
                     and a connection to our roots. Inspired by the rich and diverse flavors of African cuisine, 
                     we take pride in bringing you a blend of traditional recipes and modern twists, crafted with 
                     fresh, locally sourced ingredients.
                     Our journey began with a simple yet powerful vision: to create a space where people could 
                     come together and experience the warmth of home-cooked meals, no matter where they are.  
                     Whether you grew up savoring the rich aromas of nyama choma, the comforting texture of ugali,  
                     or the refreshing zest of a perfectly brewed dawa, we aim to bring those flavors to your 
                     table—just the way you remember them.
                     But Kwetu is more than just a restaurant. It’s a celebration of culture, heritage, and 
                     community. Our recipes are inspired by the diverse culinary traditions from across Africa,                      from the spicy stews of West Africa to the coastal delights of East Africa. Every dish tells <br>
                     a story, every spice carries a history, and every bite is a journey through the rich flavors 
                     of our homeland.
        </v-card-text>
      </v-card>
      
    </v-container>
  </div>
</template>

<style scoped>

.centered-card {
  background-color: rgba(0, 0, 0, 0.6); 
  padding: 20px;
  border-radius: 10px;
  width: 50%; 
  text-align: left;
  font-size: 12px;
}

</style>

<script setup>
import backgroundImage from '/ivan-stern-LOLSb7m6XkU-unsplash.jpg';

const backgroundStyle = {
  backgroundImage: `url(${backgroundImage})`,
  backgroundSize: 'cover',
  backgroundPosition: 'center',
  backgroundRepeat: 'no-repeat',
  height: '100vh',
  width: '100vw',
  position: 'fixed',
  top: '0',
  left: '0',
  display: 'flex',
  justifyContent: 'center',
  alignItems: 'center',
};

</script>
 -->
