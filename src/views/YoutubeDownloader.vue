<template>
  <div class="bg-pBlack h-screen pt-20">
    <div class="flex justify-center">
      <div class="bg-pdGray p-24 rounded-2xl">
        <h1 class="font-bold text-6xl">Coming Soon</h1>
      </div>
    </div>
  </div>




<!--  <div class="bg-pBlack h-screen pt-20">-->

<!--    <div class="max-w-7xl h-3/4 bg-pGrayDark flex rounded-3xl px-5 py-5 space-x-5 w-full h-full items-center justify-center mx-auto">-->

<!--      &lt;!&ndash; Settings Section &ndash;&gt;-->
<!--      <div class="h-fit w-full bg-pGray rounded-md">-->
<!--        <h1 class="p-2 px-5 py-5 font-bold text-2xl">Youtube Downloader</h1>-->

<!--        <div class="p-5">-->
<!--          <div class="grid grid-cols-1 gap-5">-->

<!--            <div class="grid gap-2 grid-cols-1 bg-pdGray p-2 py-3 rounded-xl">-->
<!--              <h2 class="text-pBlack text-lg px-1">Youtube URL</h2>-->
<!--              <input type="text" v-model="URL" placeholder="Insert Link" class="w-full p-2 rounded-lg outline-none">-->
<!--            </div>-->

<!--            <div class="grid gap-2 grid-cols-1 bg-pdGray p-2 py-3 rounded-xl">-->
<!--              <h2 class="text-pBlack text-lg px-1">Video Resolution</h2>-->
<!--              <select v-model="RESOLUTION" class="block w-52 text-gray-700 py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm" name="resolution">-->
<!--                <option value="1080p">-->
<!--                  1080p-->
<!--                </option>-->
<!--                <option value="720p">-->
<!--                  720p-->
<!--                </option>-->
<!--                <option value="480p">-->
<!--                  480p-->
<!--                </option>-->
<!--                <option value="360p">-->
<!--                  360p-->
<!--                </option>-->
<!--              </select>-->
<!--            </div>-->


<!--            <div class="grid grid-cols-2 gap-5">-->
<!--              <div class="grid gap-2 grid-cols-1 bg-pdGray w-full p-2 py-3 rounded-xl">-->
<!--                <h2 class="text-pBlack text-lg px-1">File Type</h2>-->
<!--                <select v-model="FILETYPE" class="block w-52 text-gray-700 py-2 px-3 border border-gray-300 bg-white rounded-md shadow-sm focus:outline-none focus:ring-primary-500 focus:border-primary-500" name="compression">-->
<!--                  <option value="mp4">-->
<!--                    MP4-->
<!--                  </option>-->
<!--                  <option value="webm">-->
<!--                    WEBM-->
<!--                  </option>-->
<!--                  <option value="mp3">-->
<!--                    MP3-->
<!--                  </option>-->
<!--                  <option value="wav">-->
<!--                    WAV-->
<!--                  </option>-->
<!--                </select>-->
<!--              </div>-->
<!--              <div class="grid gap-2 grid-cols-1 bg-pdGray w-full p-2 py-3 rounded-xl">-->
<!--                <h2 class="text-pBlack text-lg px-1">Start Convert</h2>-->
<!--                <button type="button" class="py-2 px-4 bg-pGreen hover:bg-pdGreen text-white w-full transition ease-in duration-200 text-center text-base font-semibold shadow-md rounded-lg ">-->
<!--                  Add to Queue-->
<!--                </button>-->
<!--              </div>-->
<!--            </div>-->

<!--          </div>-->
<!--        </div>-->
<!--      </div>-->


<!--      <div class="h-full w-full bg-pGray rounded-md">-->
<!--        &lt;!&ndash; Download Section &ndash;&gt;-->
<!--        <div class="grid grid-cols-2">-->
<!--          <h1 class="p-2 px-5 py-3 font-bold text-2xl">Download List</h1>-->
<!--        </div>-->

<!--        <div class="flex gap-3 px-6 drop-shadow-md">-->

<!--          <h1>Coming Soon...</h1>-->

<!--          &lt;!&ndash;          <a class="w-full bg-pdGray p-2 py-3 rounded-xl">&ndash;&gt;-->
<!--          &lt;!&ndash;            <h2>Max Verstappen Gaat vreemd expoosd 2002 REAL podkast</h2>&ndash;&gt;-->

<!--          &lt;!&ndash;            <img :src="{IMGURL}" class="h-32" alt="uploaded img">&ndash;&gt;-->

<!--          &lt;!&ndash;          </a>&ndash;&gt;-->

<!--          &lt;!&ndash;          &lt;!&ndash;- Download File &ndash;&gt;&ndash;&gt;-->
<!--          &lt;!&ndash;          <a class="flex gap-2 p-4 grid-cols-1 p-2 py-3 rounded-xl text-center cursor-pointer bg-pGreen hover:bg-pdGreen transition">&ndash;&gt;-->
<!--          &lt;!&ndash;            <button class="text-pBlack">&ndash;&gt;-->
<!--          &lt;!&ndash;              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 text-white">&ndash;&gt;-->
<!--          &lt;!&ndash;                <path stroke-linecap="round" stroke-linejoin="round" d="M3 16.5v2.25A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75V16.5M16.5 12L12 16.5m0 0L7.5 12m4.5 4.5V3" />&ndash;&gt;-->
<!--          &lt;!&ndash;              </svg>&ndash;&gt;-->
<!--          &lt;!&ndash;            </button>&ndash;&gt;-->
<!--          &lt;!&ndash;          </a>&ndash;&gt;-->

<!--        </div>-->
<!--      </div>-->
<!--  </div>-->
<!--</div>-->
</template>

<script>

export default {
  name: "YoutubeDownloader",
  data() {
    return {
      FILETYPE: "",
      URL: "",
      RESOLUTION: "",
    };
  },
  methods: {
    convertVideo() {

    },
  }
}
</script>