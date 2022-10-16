<template>
    <ion-page>
        <ion-toolbar>
            <ion-header>
                <ion-title>All Memories</ion-title>
            </ion-header>
        </ion-toolbar>
        <ion-content>
            <ion-list>
                <ion-item>Name like</ion-item>
            </ion-list>
        </ion-content>
    </ion-page>
</template>

<script lang="ts">
import { IonPage,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
    IonList,
    IonItem} from '@ionic/vue'
import { defineComponent } from 'vue'

export default defineComponent({
    components: {
        IonPage,
        IonHeader,
        IonToolbar,
        IonTitle,
        IonContent,
        IonList,
        IonItem
    }
})
</script>
