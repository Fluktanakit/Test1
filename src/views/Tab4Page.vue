<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 4</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 4</ion-title>
        </ion-toolbar>
      </ion-header>

<ion-content fullscreen>
        <ion-card>
          <img src="https://scontent-sin6-1.xx.fbcdn.net/v/t1.6435-9/79781132_1366275870198415_2650487162323075072_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=8bfeb9&_nc_ohc=k2zFvdOOTBgAX-8WSW5&tn=k-JZJT3E7zfTspeE&_nc_ht=scontent-sin6-1.xx&oh=00_AT83CqUq8ZcgG6t7_z5ALEIgkvoYcLopbxF54dYaRuhiqg&oe=624C6D55" />
          <ion-card-header>
            
            <ion-card-title>ธนกฤต แก้วพินิจ</ion-card-title>
          </ion-card-header>
          <ion-card-content>
            รหัสนักศึกษา : 62442206011-8
<ion-card-subtitle>เบอร์โทร : 0946013030</ion-card-subtitle>
           

          </ion-card-content>
        </ion-card>
      </ion-content>
      
     
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';


export default defineComponent({
  name: 'Tab3Page',
  components: {  IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>
