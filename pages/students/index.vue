<template>
  <div class="students">
    <div>
      <p class="home_content-ttl"><strong>生徒一覧</strong></p>
      <ul v-for="student in students" :key="student.id">
        <li><NuxtLink :to="student.name">{{student.name}}</NuxtLink></li>
      </ul>
      <NuxtLink to="/">戻る</NuxtLink>
    </div>
    
  </div>
</template>


<script>
export default {
  data() {
    return {
      students: [
        {
          id: "qnfungqxllc3m1ak",
          name: "生徒A",
        },
        {
          id: "7j9cumkgsq6l264c",
          name: "生徒B",
        },
        {
          id: "eo34bhey9m0d92ou",
          name: "生徒C",
        },
      ],
    };
  },
};
</script>


<style>
.students {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>