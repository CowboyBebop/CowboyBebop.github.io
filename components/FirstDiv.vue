<template>
  <div class="m-0 w-screen h-screen">
    <div class="flex h-full w-full">
      <div class="w-6/12 flex justify-center m-auto">
        <div class="w-11/12 mb-10 flex">
          <div class="w-2/5">
            <Logo class />
          </div>
          <div class="w-3/5 flex justify-center m-auto">
            <div>
              <div class="w-full">
                <h1 class="text-6xl leading-none .tracking-normal">OneHit</h1>
                <h2
                  class="text-2xl leading-none .tracking-normal w-full"
                >An editor, gamer and ofcourse, an HLB</h2>
              </div>
              <div class="flex justify-center mt-2 ml-2">
                <a
                  href="#process"
                  class="mr-6 ml-6 bg-transparent hover:bg-black text-black font-semibold hover:text-white py-2 px-4 border border-black hover:border-transparent rounded"
                >My process</a>
                <a
                  class="mr-6 ml-6 bg-transparent hover:bg-black text-black font-semibold hover:text-white py-2 px-4 border border-black hover:border-transparent rounded"
                >Contact me</a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="w-6/12 h-full overflow-hidden thumbnail-container">
        <div class="lg:grid grid-flow-row grid-cols-3 overflow-hidden">
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754682182739427378/Thumbnail.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754682622990614568/Amnesia_ep_2.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754682720046809108/thumbnail_for_mw.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754682814045225060/Eddie_Keeps_Failing.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754683171400056852/Doinkly-ep-1.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754683230854316112/Doinkly-ep-2.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683298738995261/Doom_Eternal_Part_5.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683323091124274/Doom_Eternal_Part_1.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683324575907920/Doom_Eternal_Part_3.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754682720046809108/thumbnail_for_mw.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754682814045225060/Eddie_Keeps_Failing.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754683171400056852/Doinkly-ep-1.png"
          />
          <img
            src="https://media.discordapp.net/attachments/686653594551845104/754682182739427378/Thumbnail.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683323091124274/Doom_Eternal_Part_1.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754682622990614568/Amnesia_ep_2.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754682622990614568/Amnesia_ep_2.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683230854316112/Doinkly-ep-2.png"
          />
          <img
            src="https://cdn.discordapp.com/attachments/686653594551845104/754683171400056852/Doinkly-ep-1.png"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
/*
.thing {
   border-solid border-8 border-white
}
*/
.thumbnail-container {
  box-shadow: inset 0px 0px 75px 75px rgba(0, 0, 0, 0.7);
}

.thumbnail-mask {
  width: 100vw;
  height: 100vh;
  mask-image: url(http://www.photoshoptutorials.tv/wp-content/uploads/2017/07/LINES.png);
  mask-repeat: repeat;
  mask-position: center center;
  mask-size: 100% 100%;
}
div.thumbnail-container div img {
  z-index: -1;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  margin-left: 10px;
}

.links {
  padding-top: 15px;
}
</style>