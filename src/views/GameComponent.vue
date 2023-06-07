<template>
    <ion-col>
        <ion-card v-bind:id="id" button="true">
            <img alt="Chrono Trigger" v-bind:src=image />
            <ion-card-header>
            <ion-card-title>{{ title }}</ion-card-title>
            <ion-card-subtitle>{{ subtitle }}</ion-card-subtitle>
            </ion-card-header>
            <ion-card-content>
                {{ description }}
            </ion-card-content>
        </ion-card>
    </ion-col>
    <ion-modal v-bind:trigger="id">
        <video controls v-bind:src="video"></video>
    </ion-modal>
</template>

<script lang="ts">
import { IonAlert, IonButton, IonModal } from '@ionic/vue';

export default {
    components: { IonAlert, IonButton, IonModal },
    props: ['title', 'subtitle', 'description', 'image', 'id', 'video'],
    setup(props) {

    } 
}
</script>

<style>
ion-modal {
    color: var(--ion-color-primary);
    --height: 80%;
    --width: 66.7%;
}
</style>
