<!--①ホーム画面-->
<template>
    <div>
      <b-container fluid>
          <b-row class="text-center my-3 py-3">
              <b-col>
                  <h1>投稿した講義ノート</h1>
              </b-col>
          </b-row>
          <b-row class="text-center muy-3">
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
          </b-row>
          <b-row class="text-center my-3">
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
              <b-col cols="4"><img src="" alt="ピックアップコンテンツ1"></b-col>
          </b-row>
      </b-container>
    </div>
</template>

<script>
import IndexMain from '~/components/pages/IndexMain.vue'

export default{
    components: {
        IndexMain
    }
}
</script>