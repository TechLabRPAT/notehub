<!--③各種講義ノート詳細-->
<template>
    <div>
        <b-container fluid>
            <b-row class="text-center py-3">
                <b-col>
                    <h2>講義名</h2>
                </b-col>
            </b-row>
            <b-row class="text-center py-２">
                <b-col cols="1"></b-col>
                <b-col cols="10">
                    <div class="img-box">
                        <img class="object-fit_contain" src="~assets/note.jpg" alt="" />
                    </div>
                </b-col>
                <b-col cols="1"></b-col>
            </b-row>
            <b-row class="text-center">
                <b-col cols="1"></b-col>
                <b-col cols="10">
                    <p>"投稿者コメント"</p>
                </b-col>
                <b-col cols="1"></b-col>
            </b-row>
            <b-row class="text-center py-3">
                <b-col cols="4">
                    <n-link to="/">
                        <p>出品者情報</p>
                    </n-link>
                </b-col>
                <b-col cols="4">
                    <p>カテゴリ</p>
                    <p>カテゴリ名</p>
                </b-col>
                <b-col cols="4">
                    <p>ノート評価</p>
                    <p>〇〇pt</p>
                </b-col>
            </b-row>
            <b-row class="text-center my-2">
                <b-col cols="2">
                    <a href="">報告</a>
                </b-col>
                <b-col cols="8">
                    <a href="">
                        <b-button>　　今すぐ読む　　</b-button>
                    </a>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
import '~/assets/css/styles.css'

export default {
    
}
</script>