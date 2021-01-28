<template>
  <div>
    <div class="container column is-10">
      <nuxt />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: "Mot de passe oublié",
          to: { name: "forgotten-pwd" },
        },
      ],
    };
  },
};
</script>
