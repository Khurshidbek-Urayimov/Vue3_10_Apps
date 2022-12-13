<template>
  <AppHeader/>
  <div class="w-full flex">
<!--    <DcHeros />-->
    <CalendarApp />
  </div>
</template>
<script>
import AppHeader from "@/components/AppHeader.vue";
import CalendarApp from "@/components/Calendar.vue";
// import DcHeros from "@/components/DcHeros.vue";
export default {
  components:{
    CalendarApp,
    // DcHeros,
    AppHeader,
  },
}
</script>