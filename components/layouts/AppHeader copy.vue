<template>
    <header class="sticky-top">
        <div class="d-flex justify-content-between">
            <div>
                <a href="/">
                  <img src="~assets/logo.png" alt="大学講義ノートアプリ">
                </a>
            </div>
            <form action="" class="w-auto p-4">
              <div class="searchArea" id="makeImg">
                <input type="text" id="inText" class="searchText">
                <div class="searchButton">
                  <span>検索</span>
                </div>
             </div>
                  <i class="icon">
                  </i>
            </form>
            <div>
            </div>
        </div>
        <nav class="d-flex justify-content-around">
            <div>
                <b-dropdown id="dropdown-1" text="カテゴリーから探す" class="m-md-2">
                  <b-dropdown-item>1つ目のアクション</b-dropdown-item>
                  <b-dropdown-item>Second Action</b-dropdown-item>
                  <b-dropdown-item>Third Action</b-dropdown-item>
                  <b-dropdown-divider></b-dropdown-divider>
                  <b-dropdown-item active>Active action</b-dropdown-item>
                  <b-dropdown-item disabled>Disabled action</b-dropdown-item>
                </b-dropdown>
                </div>
            <div>
                <a href=""><button type="button" class="btn btn-primary">Login</button></a>
            </div>
        </nav>
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