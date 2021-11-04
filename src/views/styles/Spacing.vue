<!--컴포넌트 UI 정의-->
<template>
  <v-card>
    <v-card-title>Margin and Padding</v-card-title>
    <v-card-text>
      <div class="yellow pa-3">
        <div class="indigo lighten-3 green--text ml-13 mr-5">
          Adjust screen size to see spacing changes
        </div>
        <div class="indigo lighten-3 green--text mt-5 ml-13 mr-5">
          Adjust screen size to see spacing changes
        </div>
        <div class="indigo lighten-3 green--text ma-3 pa-5">
          Adjust screen size to see spacing changes
        </div>
      </div>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  //컴포넌트의 대표 이름(devtools에 나오는 이름)
  name: "",
  //추가하고 싶은 컴포넌트들 목록
  components: {},
  //컴포넌트 데이터 정의
  data: function () {
    return {};
  },
  //컴포넌트 메소드 정의
  methods: {},
};
</script>

<!--컴포넌트 스타일 정의-->
<!--scoped를 생략하면 전역으로 사용-->
<style scoped></style>
