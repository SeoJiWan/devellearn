<template>
  <div id="box">
    <!-- 부트스트랩 -->
    <form>
      <div class="form-group">
        <label for="recipient-name" class="col-form-label">Recipient:</label>
        <input type="text" class="form-control" id="recipient-name" />
      </div>
      <div class="form-group">
        <label for="message-text" class="col-form-label">Message:</label>
        <textarea class="form-control" id="message-text"></textarea>
      </div>
    </form>

    <!-- 부트스트랩 -->
  </div>
</template>
<script>
export default {
  components: {},
};
</script>
<style scoped>
#box {
  width: 450px;
  margin: 0 auto;
}
</style>
