<template>
  <div>
    <!--此处的props加了:-->
    <van-field
      v-model="content"
      :label="label"
      :type="type"
      :placeholder="placeholder"
      :rules="rule"
    />
  </div>
</template>

<script>
export default {
  data () {
    return {
      content: ''
    }
  },
  props: ['label', 'type', 'placeholder', 'rule'],
  methods: {
    handlerulg () {
      const rue = new RegExp(this.rules)
      if (rue.test(this.content)) {
        console.log('success')
      }
    }
  },
  watch: {
    content () {
      this.handlerulg()
    }
  }
}
</script>

<style>

</style>
