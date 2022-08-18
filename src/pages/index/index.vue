<template>
  <view class="index">
    <template v-if="item.patientInfo !== 1">hahaha</template>
    <text>{{ msg }}</text>
    <textarea
      :value="keyword"
      type="text"
      style="height:28px;"
    />
  </view>
</template>

<script>
import './index.scss'

export default {
  data () {
    return {
      msg: 'Hello world!',
      item:{
        patientInfo: 0
      },
      keyword:''
    }
  }
}
</script>
