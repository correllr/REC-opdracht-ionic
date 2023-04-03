<template>
  <ion-page>
    <toolbarHeader />
    <ion-content :fullscreen="true">
      <mainHome name="Tab 3 page" />
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonContent } from '@ionic/vue';
import mainHome from '@/components/mainHome.vue';
import toolbarHeader from '@/components/toolbarHeader.vue';
</script>
