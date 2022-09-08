<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@ionic/core@4.7.4/css/ionic.bundle.css"/>
  <style>
    :root {
      --ion-safe-area-top: 20px;
      --ion-safe-area-bottom: 22px;
    }
  </style>
<template>
  <ion-page>
    <ion-header translucent>
      <ion-toolbar>
        <ion-title>Blink Delivery</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Comanda</ion-title>
        </ion-toolbar>
      </ion-header>
      <ion-searchbar animated 
                    placeholder="Descopera poftele de azi"
                    show-cancel-button="focus"></ion-searchbar>
    <ion-list inset="true">
      <ion-card button="true" color="primary">
          <ion-card-header>
            <ion-card-title>KungFu King</ion-card-title>
            <ion-card-subtitle>Specific Asiatic</ion-card-subtitle>
          </ion-card-header>
    </ion-card>
    <ion-card button="true" color="primary">
          <ion-card-header>
            <ion-card-title>Toan's</ion-card-title>
            <ion-card-subtitle>Specific Vietnamez</ion-card-subtitle>
          </ion-card-header>
    </ion-card>
    <ion-card button="true" color="primary">
          <ion-card-header>
            <ion-card-title>Casa Romaneasca</ion-card-title>
            <ion-card-subtitle>Specific Romanesc</ion-card-subtitle>
          </ion-card-header>
    </ion-card>
    <ion-card button="true" color="primary">
          <ion-card-header>
            <ion-card-title>Tatu Bar&Grill</ion-card-title>
            <ion-card-subtitle>Specific Romanesc</ion-card-subtitle>
          </ion-card-header>
    </ion-card>
    </ion-list>
    
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
//import ExploreContainer from '@/components/ExploreContainer.vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
