<template>
  <div>
    <h1>Hi, I have 2 inline components</h1>
    <MyButton />
    <UserName name="Demi more" />
  </div>
</template>

<script>
//Inline component with template string
const MyButton = {
  template: `<h1>My Button</h1>`,
};

//Inline component with template string and props
const UserName = {
  props: ["name"],
  template: "<p>Hi {{ name }}</p>",
};

export default {
  components: {
    MyButton,
    UserName,
  },
};
</script>

<style lang="scss" scoped></style>
