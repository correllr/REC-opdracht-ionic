<template>
    <ion-content>
      <ion-list>
        <ion-item href="/tabs/tab1">
          <ion-icon aria-hidden="true" :icon="documentTextOutline" color="primary" />
          <ion-label>Toegewezen Rapportages</ion-label>
        </ion-item>
        <ion-item  href="/tabs/tab2">
          <ion-icon aria-hidden="true" :icon="fileTrayFullOutline" color="primary" />
          <ion-label>Uitgevoerd Rapportages</ion-label>
        </ion-item>
        <ion-item href="/tabs/tab3">
          <ion-icon aria-hidden="true" :icon="bookOutline" color="primary" />
          <ion-label>Knowledge Base</ion-label>
        </ion-item>
        <ion-item href="/tabs/tab4">
          <ion-icon aria-hidden="true" :icon="settingsOutline" color="primary" />
          <ion-label>Instellingen</ion-label>
        </ion-item>
      </ion-list> 
    </ion-content>
</template>
<script setup lang="ts">
import { IonIcon,IonContent, IonLabel, IonList, IonItem} from '@ionic/vue';
import { bookOutline, fileTrayFullOutline, documentTextOutline, settingsOutline} from 'ionicons/icons';
</script>
<style scoped>
  ion-item {
    height: 4rem;
    display: flex;
    align-items: center;
  }

  ion-item ion-icon {
    padding-right: 1rem;
  }

</style>