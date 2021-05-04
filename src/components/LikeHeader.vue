<template>
  <div>
    <slot name="title" :user="user"></slot>
    <hr>
    <slot></slot>
    <p>いいねの数</p>
    <slot name="number"></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: "Jack",
        lastName: "Donald"
      }
    }
  }
}
</script>