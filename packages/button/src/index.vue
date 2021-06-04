<template>
  <div class="app-button">
    <button>
      <slot></slot>
    </button>
  </div>
</template>
<script>
export default {
  name: "AppButton",
};
</script>
<style lang="scss" scoped>
.app-button {
  > button {
    border: 1px solid #d9d9d9;
    border-radius: 2px;
    padding: 4px 16px;
    background: #fff;
    color: rgba(0, 0, 0, 0.85);
    font-size: 14px;
    text-align: center;
    font-weight: 400;
    height: 32px;
    box-sizing: border-box;
  }
}
</style>
