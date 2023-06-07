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
    <ion-alert 
        v-bind:trigger="id" 
        class="custom-alert" 
        v-bind:header=title
        subHeader="Trailer">
        <iframe 
            height="720px"
            width="1280px"
            controls
            v-bind:src="video">
        </iframe>
    </ion-alert>
</template>

<script lang="ts">
import { IonAlert, IonButton } from '@ionic/vue';

export default {
    components: { IonAlert, IonButton },
    props: ['title', 'subtitle', 'description', 'image', 'id', 'video'],
    setup(props) {

    } 
}
</script>

<style>
ion-alert {
    color: var(--ion-color-primary);
}
</style>
