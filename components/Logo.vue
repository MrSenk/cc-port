<template>
  <div class="avatar-border">
    <img class="avatar" src="~/assets/spooderman.png" />
  </div>
</template>

<style>
.avatar {
  animation: 1s appear;
  margin: auto;
  width: 300px;
  height: 300px;
  border-radius: 50%;
}

.avatar-border {
  width: 350px;
  height: 350px;
  border-radius: 50%;
  border: solid 10px black;
  padding: 15px;
  background-color: red;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
