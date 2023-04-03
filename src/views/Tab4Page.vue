<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 4</ion-title>
        </ion-toolbar>
      </ion-header>

      <mainHome name="Tab 4 page" />
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import mainHome from '@/components/mainHome.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
