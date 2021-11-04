<!--컴포넌트 UI 정의-->
<template>
  <v-card>
    <v-card-title>Grid System</v-card-title>
    <v-card-text>
      <v-row>
        <v-col class="green" cols="12" sm="2" md="6" lg="10">A</v-col>
        <v-col class="yellow" cols="12" sm="10" md="6" lg="2">B</v-col>
      </v-row>
      <v-row class="indigo lighten-3">
        <v-col cols="12" sm="2" md="6" lg="10">A</v-col>
        <v-col cols="12" sm="10" md="6" lg="2">B</v-col>
      </v-row>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  //컴포넌트의 대표 이름(devtools에 나오는 이름)
  name:"",
  //추가하고 싶은 컴포넌트들 목록
  components:{
  },
  //컴포넌트 데이터 정의
  data: function() {
    return {
    };
  },
  //컴포넌트 메소드 정의
  methods:{
  }
}
</script>

<!--컴포넌트 스타일 정의-->
<!--scoped를 생략하면 전역으로 사용-->
<style scoped>

</style>