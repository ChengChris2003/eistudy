<template>
  <!-- 这里定义页面的高度，calc(100vh - 84px) 是为了减去顶部导航栏的高度，避免出现双滚动条 -->
  <div style="height: calc(100vh - 84px); width: 100%;">
    <iframe 
      src="http://43.140.245.165:8993/chat/w5lEhYVkPkdEADSu" 
      width="100%" 
      height="100%" 
      frameborder="0"
      allow="microphone">
    </iframe>
  </div>
</template>

<script>
export default {
  name: "AiChat"
}
</script>