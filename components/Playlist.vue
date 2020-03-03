<template>
  <div>
    <b-row class="playlist">
      <b-col cols="auto" class="mr-auto">
        <h2>{{ title }}</h2>
      </b-col>
      <b-col cols="auto" class="">
        <h4>ดูทั้งหมด</h4>
      </b-col>
    </b-row>
    <hooper class="slide-box" :settings="hooperSettings">
      <slide>
        <div class="img">
          <img src="https://picsum.photos/600/300/?image=25">
        </div>
        <div class="title">
          ชื่อเพลงๆๆๆๆๆ
        </div>
      </slide>
      <slide>
        <div class="img">
          <img src="https://picsum.photos/600/300/?image=26">
        </div>
        <div class="title">
          ชื่อเพลงๆๆๆๆๆ
        </div>
      </slide>
      <slide>
        <div class="img">
          <img src="https://picsum.photos/600/300/?image=27">
        </div>
        <div class="title">
          ชื่อเพลงๆๆๆๆๆ
        </div>
      </slide>
      <slide>
        <div class="img">
          <img src="https://picsum.photos/600/300/?image=28">
        </div>
        <div class="title">
          ชื่อเพลงๆๆๆๆๆ
        </div>
      </slide>
      <slide>
        <div class="img">
          <img src="https://picsum.photos/600/300/?image=29">
        </div>
        <div class="title">
          ชื่อเพลงๆๆๆๆๆ
        </div>
      </slide>
    </hooper>
  </div>
</template>

<script>
import { Hooper, Slide } from 'hooper'
import 'hooper/dist/hooper.css'

export default {
  components: {
    Hooper,
    Slide
  },
  props: [
    'title'
  ],
  data () {
    return {
      hooperSettings: {
        itemsToShow: 4,
        infiniteScroll: true
      }
    }
  },
  methods: {
    // next () {
    //   this.$refs.flickity.next()
    // },
    // previous () {
    //   this.$refs.flickity.previous()
    // }
  }
}
</script>
