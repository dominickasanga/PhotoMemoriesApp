<template>
    <ion-page>
        <base-layout :pageTitle="title">
            <ion-list>
                <ion-item router-link="/memories/1">Hiking</ion-item>
                <ion-item>Park Visit</ion-item>
            </ion-list>
        </base-layout>
    </ion-page>
</template>

<script lang="ts">
import BaseLayout from '@/components/base/BaseLayout.vue'
import { 
        IonList,
        IonItem

    } from '@ionic/vue'
import { defineComponent } from 'vue'

export default defineComponent({
    components: {
        IonList,
        IonItem,
        BaseLayout
    },
    data: () =>  ({
        title: "All The Memories"
    })
})
</script>
