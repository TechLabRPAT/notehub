<template>
    <div>
        <b-container fluid>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <n-link to="/"><b-img src="~/assets/logo.png" alt="ロゴ画像" fluid></b-img></n-link>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <h2>購入内容の確認</h2>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <h2>講義ノート名</h2>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <h2>{保有ポイント数}</h2>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <h2>必要ポイント数</h2>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center py-2 my-2">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <b-button>
                        <h2>購入する</h2>
                    </b-button>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
        </b-container>
    </div>
</template>
<script>
export default{
   layout: 'space'
}
</script>