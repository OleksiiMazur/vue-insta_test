<template>
    <vue-instagram
        token="7089887265.1677ed0.f3d1f012770e4c1ba11e0d00311aefdc"
        :count="5"
        :tags="[]"
        mediaType="image"
    >
        <template slot="feeds" slot-scope="props">
            <li class="fancy-list"> {{ props.feed.link }}</li>
        </template>
        <template slot="error" slot-scope="props">
            <div class="fancy-alert"> {{ props.error.error_message }}</div>
        </template>
    </vue-instagram>
</template>

<script>
    import VueInstagram from 'vue-instagram'

    export default {
        name: 'App',

        components: {
            VueInstagram
        }
    }
</script>