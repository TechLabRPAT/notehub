<template>
    <div>
        <b-container fluid>
            <b-row class="text-center my-3 py-3">
                <b-col cols="3"></b-col>
                <b-col cols="6">
                    <h1>CONTACT</h1>
                    <h3>ーお問い合わせー</h3>
                </b-col>
                <b-col cols="3"></b-col>
            </b-row>
            <b-row class="text-center my-3 py-3">
                <b-col cols="2"></b-col>
                <b-col cols="8">
                    <h3>下記のフォームに必要事項をご記入の上、送信ください。</h3>
                </b-col>
                <b-col cols="2"></b-col>
            </b-row>
            <b-row class="text-center my-3 py-3">
                <b-col class="text-right" cols="4">
                    <h3>メールアドレス</h3>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="6">
                    <div class="input-group">
                        <b-form-input type="text" class="form-control" placeholder="メールアドレスをご入力ください"></b-form-input>
                    </div>
                </b-col>
            </b-row>
            <b-row class="text-center my-3 py-3">
                <b-col class="text-right" cols="4">
                    <h3>お問い合わせ内容</h3>
                </b-col>
                <b-col cols="2"></b-col>
                <b-col cols="6">
                    <b-form-textarea rows="5" placeholder="お問い合わせ内容をご入力ください">

                    </b-form-textarea>
                </b-col>
            </b-row>
            <b-row class="text-center my-3 py-3">
                <b-col cols="3"></b-col>
                <b-col cols="6">
                    <b-button variant="outline-primary">送信</b-button>
                </b-col>
                <b-col cols="3"></b-col>
            </b-row>
        </b-container>
    </div>
</template>