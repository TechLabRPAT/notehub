<template>
  <header>
  <b-container fluid>
    <b-row class="text-center my-2">
      <b-col cols="2">
        <n-link to="/"><b-img src="~/assets/logo.png" alt="ロゴ画像" fluid></b-img></n-link>
      </b-col>
      <b-col cols="2"></b-col>
      <b-col cols="4"></b-col>
      <b-col cols="4">
        <a href=""><button type="button" class="btn btn-outline-primary">Login</button></a>
      </b-col>
    </b-row>
    <b-row class="text-center">
      <b-col cols="12">
        <div class="input-group">
          <b-form-input type="text" class="form-control" placeholder="search"></b-form-input>
          <span class="input-group-btn pxr-2">
            <b-button variant="outline-primary">検索</b-button>
          </span>
        </div>
      </b-col>
    </b-row>
    <b-row class="text-center my-3">
      <b-col cols="4">
         <b-button-group>
          <b-dropdown right text="category" variant="outline-danger">
            <b-dropdown-item>Item 1</b-dropdown-item>
            <b-dropdown-item>Item 2</b-dropdown-item>
            <b-dropdown-divider></b-dropdown-divider>
            <b-dropdown-item>Item 3</b-dropdown-item>
          </b-dropdown>
        </b-button-group>
      </b-col>
      <b-col cols="4"></b-col>
      <b-col cols="4">
        <n-link to="/detail"><button type="button" class="btn btn-outline-dark">詳細検索</button></n-link>
      </b-col>
    </b-row>
  </b-container>
  </header>
</template>

<script>
import Logo from '~/components/Logo.vue'
import '~/assets/css/styles.css'

export default {
  components: {
    Logo
  }
}
</script>