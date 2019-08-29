<template>
    <div>
        <header>
             <b-container fluid>
                <b-row class="text-center my-2">
                    <b-col cols="2">
                        <n-link to="/"><b-img src="~/assets/logo.png" alt="/" fluid></b-img></n-link>
                    </b-col>
                    <b-col cols="2"></b-col>
                    <b-col cols="4"></b-col>
                    <b-col cols="2">
                        <a href=""><button type="button" class="btn btn-outline-primary">Login</button></a>
                </b-col>
                </b-row>
             </b-container>
        </header>
        <nuxt />
        <AppFooter />
    </div>
</template>

<script>
import AppFooter from '~/components/Layouts/AppFooter.vue'

export default {
  components: {
    AppFooter
  }
}

</script>