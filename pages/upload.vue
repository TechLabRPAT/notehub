<template>
  <div>
    <b-row class="text-center">
      <b-col>
        <h4>ノートの情報を入力してください</h4>
      </b-col>
    </b-row>
    <b-row class="mt-4">
      <b-col cols="3"></b-col>
      <b-col cols="auto" class="text-left">
        <h5 class="border border-dark">ノート紙面画像</h5>
      </b-col>
      <b-col class="text-left">
        <h6 class=""><small>※最初の1枚がサムネイルとして表示されます</small></h6>    
      </b-col>
        <!-- 同じ行に違う大きさの文字を隙間なく表示したい -->
        <!-- 大きさの違う文字の下端をそろえたい -->
    </b-row>
    <!-- Styled -->
    <b-row align-h="center">     
      <b-col cols="5">
        <b-form-file
          v-model="file"
          :state="Boolean(file)"
          placeholder="画像ファイルを選択してください"
          drop-placeholder="Drop file here..."
          ></b-form-file>
      </b-col>
    </b-row>
    <b-row class="mt-3">
      <b-col cols="3"></b-col>
      <b-col cols="auto" class="">
        <h5>ノートタイトル</h5>
      </b-col>
    </b-row>
    <b-row align-h="center">
        <b-col cols="5">
          <b-form-input v-model="text" placeholder="Enter note title"></b-form-input>
        </b-col>
    </b-row>

    <b-row class="mt-3">
      <b-col cols="3"></b-col>
      <b-col cols="auto" class="">
        <h5>講義ノート概要（投稿者コメント）</h5>
      </b-col>
    </b-row>
    <b-row align-h="center">
      <b-col cols="5">
        <b-form-textarea
          id="textarea"
          v-model="text"
          placeholder="Enter something..."
          rows="2"
          max-rows="3"
          ></b-form-textarea>
      </b-col>
    </b-row>

    <b-row class="mt-3">
      <b-col cols="3"></b-col>
      <b-col cols="auto" class="">
        <h5>ノートの詳細</h5>
      </b-col>
    </b-row>
    <b-container fluid>
      <b-row class="my-1" v-for="type in types1" :key="type" align-h="center">
        <b-col cols="1">
          <label :for="`type-${type}`">{{ type }}:</label>
        </b-col>
        <b-col cols="5">
          <b-form-input :id="`type-${type}`" :type="type"></b-form-input>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid>
      <b-row class="my-1" align-h="center">
        <b-col cols="1">
          学部:
        </b-col>
        <b-col cols="5">
          <b-form-select v-model="selected" :options="options"></b-form-select>
        </b-col>
      </b-row>
    </b-container>

    <b-container fluid>
      <b-row class="my-1" v-for="type in types2" :key="type" align-h="center">
        <b-col cols="1">
          <label :for="`type-${type}`">{{ type }}:</label>
        </b-col>
        <b-col cols="5">
          <b-form-input :id="`type-${type}`" :type="type"></b-form-input>
        </b-col>
      </b-row>
    </b-container>    

    <b-row class="my-3" align-h="center">
      <div>
        <b-button v-b-modal.modal-1>アップロード</b-button>
        <b-modal id="modal-1" title="BootstrapVue">
          <p class="my-4">Hello from modal!</p>
        </b-modal>
      </div>
    </b-row>

    <b-row align-h="center" class="my-3">
      <button type="button" onclick="history.back()">戻る</button>
    </b-row>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        file: null,
        file2: null,
        types1: [
          '講義名',
          '教授名'
        ],
        types2: [
          'date'
        ],
        selected: null,
        options:[
          { Value: '政治経済学部', text: '政治経済学部' },
          { Value: '法学部', text: '法学部' },
          { Value: '文化構想学部', text: '文化構想学部' },
          { Value: '文学部', text: '文学部' },
          { Value: '教育学部', text: '教育学部' },
          { Value: '商学部', text: '商学部' },
          { Value: '基幹理工学部', text: '基幹理工学部' },
          { Value: '創造理工学部', text: '創造理工学部' },
          { Value: '先進理工学部', text: '先進理工学部' },
          { Value: '社会科学部', text: '社会科学部' },
          { Value: '人間科学部', text: '人間科学部' },
          { Value: 'スポーツ科学部', text: 'スポーツ科学部' },
          { Value: '国際教養学部', text: '国際教養学部' }
        ]
      }
    }
  }
</script>