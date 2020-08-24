<template>
  <div id="cards-holder">
      <div v-for="brand in brands" :key="brand.title" class="single-card">
      <Card v-bind:data="brand" />
      </div>
  </div>
</template>

<script>
import Card from './Card';
export default {
components: {
    Card
},

data () {
    return{
        brands: [
            {title: 'Apple Inc.', image: 'https://www.stickpng.com/img/download/580b57fcd9996e24bc43c516/image', logo: 'Apple Logo', time: '02d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'},
            {title: 'Nike Inc.', image: 'https://www.stickpng.com/img/download/5a7f5f1fabc3d121aba71180/image', logo: 'Nike Logo', time: '02d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'},
            {title: 'Samsung Inc.', image: 'https://www.stickpng.com/img/download/580b57fcd9996e24bc43c533/image', logo: 'Samsung Logo', time: '89d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'},
            {title: 'Evernote Inc.', image: 'https://www.stickpng.com/img/download/5847f3a8cef1014c0b5e4881/image', logo: 'Evernote Logo', time: '02d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'},
            {title: 'Twitter Inc.', image: 'https://www.stickpng.com/img/download/580b57fcd9996e24bc43c53e/image', logo: 'Twitter Logo', time: '02d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'},
            {title: 'SoundCloud Inc.', image: 'https://www.stickpng.com/img/download/580b57fcd9996e24bc43c537/image', logo: 'SoundCloud Logo', time: '02d:15h:33m', task: 'iOS 10 Lead Team Design', teamNo: '89', budgetNo: '$88.5m', successRate : '16.9%', teams: 'teams', budget: 'budget', success: 'success'}

            ]
    }
    }
}
</script>

<style>
#cards-holder{
    margin-top: 55px;
    padding-top: 25px;
    margin-left: 300px;
}

.single-card{
    display: inline-block;
    padding-bottom: 30px;
}

</style>