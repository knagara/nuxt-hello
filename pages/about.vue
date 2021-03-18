<template>
  <div>
    <h1>About</h1>
    <nuxt-link to="/">TOP</nuxt-link>
  </div>
</template>

<script>
export default {
  head() {
    return {
      // タイトルテンプレートがある場合は "ABOUT - ポートフォリオ" になる
      title: "About",
      meta: [
        { hid: "description", name: "description", content: "About ページ" },
      ],
    };
  },
  layout: "dark",
};
</script>