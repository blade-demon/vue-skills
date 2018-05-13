
<template>
<div>
<h1>Hello {{ their_name }}, this is an about page</h1>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti ut optio officiis, dolorum aspernatur reiciendis accusantium itaque, nisi pariatur quisquam, obcaecati eaque placeat nesciunt? Rerum, cupiditate. Qui, explicabo suscipit. Tenetur?
  </p>
</div>

</template>

<script>
export default {
  name: "About",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>

<style>

</style>

