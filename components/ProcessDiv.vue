<template>
  <section class="flex m-0 w-screen h-screen process-div">
    <div class="w-2/5">
      <div
        breakpoint="(min-height: 80px)"
        class="flex justify-center mt-2 space-x-2"
      >
        <img
          class="editing-gif mt-24 ml-16"
          src="https://media.discordapp.net/attachments/686653594551845104/755040722658394112/download.gif"
        />
      </div>
    </div>
    <div class="w-3/5 mt-16">
      <h1 class="text-6xl font-serif text-center">My Process</h1>
      <p class="text-2xl font-serif">1. I do stuff</p>
      <p class="text-2xl font-serif">2. Then i do more stuff</p>
      <p class="text-2xl font-serif">3. We do this stuff</p>
      <p class="text-2xl font-serif">4. ????</p>
      <p class="text-2xl font-serif">5. Profit</p>
    </div>
  </section>
</template>

<script></script>
<style>
.editing-gif {
  width: 450px;
  height: 300px;
}

/*
.process-div {
}
*/
.process-div h1,
p {
  color: black;
}
</style>
