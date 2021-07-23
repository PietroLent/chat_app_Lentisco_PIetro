<!-- Sostituirà i div nella sidebar e al click, cambierà il contenuuto della BoxChat  e aggiornerà
il primo div, che indica la chat corrente-->
<template>
<div>
  <div class="chat_people">
    <div class="chat_img">
      <img src="https://cdn2.iconfinder.com/data/icons/people-round-icons/128/man_avatar-512.png" alt="Avatar"> </div>
    <div class="chat_ib">
      <h5>{{ ChatList.user }}<span class="chat_date">{{ ChatList.data }}</span></h5>
      <p>{{ ChatList.messages[messages.length]}}</p>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: 'Chat'
}
</script>


<style scoped>

</style>
