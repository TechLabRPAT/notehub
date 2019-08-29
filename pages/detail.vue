<!--②条件指定画面-->
<template>
        <div>
        <b-container fluid>
            <b-row class="text-center my-3 py-3">
                <b-col>
                    <h3>詳細検索</h3>
                </b-col>
            </b-row>
            <b-row class="my-3 py-3">
                <b-col class="text-right" cols="4">
                    <h3>講義名</h3>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="6">
                    <div class="input-group">
                        <b-form-input type="text" class="form-control" placeholder="search"></b-form-input>
                    </div>
                </b-col>
            </b-row>
            <b-row class="my-3 py-3">
                <b-col class="text-right" cols="4">
                    <h3>教授名</h3>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="6">
                    <div class="input-group">
                        <b-form-input type="text" class="form-control" placeholder="search"></b-form-input>
                    </div>
                </b-col>
            </b-row>
            <b-row class="my-3 py-3">
                <b-col class="text-right" cols="4">
                    <h3>学部</h3>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="6">
                    <div class="input-group">
                        <b-form-input type="text" class="form-control" placeholder="search"></b-form-input>
                    </div>
                </b-col>
            </b-row>
        </b-container>
                <b-container fluid>
            <b-row class="text-center my-3 py-3">
                <b-col>
                    <h3>評価ランク</h3>
                </b-col>
            </b-row>
            <b-row class="my-3 py-3">
                <b-col class="text-right" cols="5">
                    <b-button-group>
                    <b-dropdown right text="以上" variant="outline-danger">
                        <b-dropdown-item>1</b-dropdown-item>
                        <b-dropdown-item>2</b-dropdown-item>
                        <b-dropdown-item>3</b-dropdown-item>
                        <b-dropdown-item>4</b-dropdown-item>
                        <b-dropdown-item>5</b-dropdown-item>
                    </b-dropdown>
                    </b-button-group>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="5">
                    <b-button-group>
                    <b-dropdown right text="以下" variant="outline-danger">
                        <b-dropdown-item>1</b-dropdown-item>
                        <b-dropdown-item>2</b-dropdown-item>
                        <b-dropdown-item>3</b-dropdown-item>
                        <b-dropdown-item>4</b-dropdown-item>
                        <b-dropdown-item>5</b-dropdown-item>
                    </b-dropdown>
                    </b-button-group>
                </b-col>
            </b-row>
                        <b-row class="text-center my-3 py-3">
                <b-col>
                    <h3>講義年月日</h3>
                </b-col>
            </b-row>
            <b-row class="my-3 py-3">
                <b-col class="text-right" cols="5">
                    <b-button-group>
                    <b-dropdown right variant="outline-danger">
                        <b-dropdown-item>Item 1</b-dropdown-item>
                        <b-dropdown-item>Item 2</b-dropdown-item>
                        <b-dropdown-divider></b-dropdown-divider>
                        <b-dropdown-item>Item 3</b-dropdown-item>
                    </b-dropdown>
                    </b-button-group>
                    <p>から</p>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="5">
                    <b-button-group>
                    <b-dropdown right variant="outline-danger">
                        <b-dropdown-item>Item 1</b-dropdown-item>
                        <b-dropdown-item>Item 2</b-dropdown-item>
                        <b-dropdown-divider></b-dropdown-divider>
                        <b-dropdown-item>Item 3</b-dropdown-item>
                    </b-dropdown>
                    </b-button-group>
                    <p>まで</p>
                </b-col>
            </b-row>
            <b-row class="text-center my-3 py-3">
                <b-col>
                    <span class="pxr-2">
                        <b-button variant="outline-primary"><h3>検索</h3></b-button>
                    </span>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>

export default{
   layout: 'detail'
}   
</script>