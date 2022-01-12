<template>
  <div class="custom-select rounded-3xl" :tabindex="tabindex" @blur="open = false">
    <div
      class="selected text-primary text-lg px-4"
      :class="{ open: open }"
      @click="open = !open"
    >
      {{ selected }}
    </div>
    <div class="items" :class="{ selectHide: !open }">
      <div
        v-for="(option, i) of options"
        :key="i"
        @click="
          selected = option
          open = false
          $emit('input', option)
        "
        class="bg-Neutral-Grey6 border-b-2 border-Neutral-Grey3 hover:bg-Neutral-Grey5 transition"
      >
        {{ option }}
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    options: {
      type: Array,
      required: true,
    },
    default: {
      type: String,
      required: false,
      default: null,
    },
    tabindex: {
      type: Number,
      required: false,
      default: 0,
    },
  },
  data() {
    return {
      selected: this.default
        ? this.default
        : this.options.length > 0
        ? this.options[0]
        : null,
      open: false,
    }
  },
  mounted() {
    this.$emit('input', this.selected)
  },
}
</script>
<style scoped>
.custom-select {
  width: 228px;
  height: 35px;
  background-color: white;
  position: relative;
  text-align: right;
  outline: none;
}
.custom-select .selected {
  
  
  cursor: pointer;
  user-select: none;
}
.custom-select .selected:after {
  position: absolute;
  content: '';
  top: 10.5px;
  left: 1rem;
  width: 14px;
  height: 14px;
  background-image: url('../../assets/images/downarrow.svg');
}
.custom-select .items {
  border-radius: 0px 0px 6px 6px;
  overflow: hidden;
  position: absolute;
  background-color: transparent;
  left: 0;
  right: 0;
  z-index: 1;
}
.custom-select .items div {
  padding-left: 1em;
  cursor: pointer;
  user-select: none;
}
.selectHide {
  display: none;
}
</style>
