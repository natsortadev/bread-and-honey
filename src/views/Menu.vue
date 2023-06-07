<template>
    <ion-menu side="start" content-id="main-content">
        <ion-header>
            <ion-toolbar>
                <ion-title>Geno's Forest Grove</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content class="ion-padding">
            There are many secrets in this land<br>
            Up in the clouds<br>
            Or beneath the sand<br>
            Deep within this forest there is a place<br>
            If you go looking you might go insane
        </ion-content>
    </ion-menu>
</template>

<script lang="ts">
import { heart, leaf, logoIonic, star } from 'ionicons/icons';
import {
    IonButtons,
    IonContent,
    IonHeader,
    IonMenu,
    IonMenuButton,
    IonPage,
    IonTitle,
    IonToolbar,
    IonIcon,
} from '@ionic/vue';
import {
  archiveOutline,
  archiveSharp,
  bookmarkOutline,
  bookmarkSharp,
  heartOutline,
  heartSharp,
  mailOutline,
  mailSharp,
  paperPlaneOutline,
  paperPlaneSharp,
  trashOutline,
  trashSharp,
  warningOutline,
  warningSharp,
} from 'ionicons/icons';

export default {
    components: {
        IonButtons,
        IonContent,
        IonHeader,
        IonMenu,
        IonMenuButton,
        IonPage,
        IonTitle,
        IonToolbar
    }
}
</script>