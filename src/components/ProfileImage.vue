<template>
  <img
    :src="profileImage"
    alt="Profile Photo"
    class="h-8 w-8 rounded-3xl object-contain"
  />
</template>

<script>
export default {
  name: "ProfileImage",
  data: () => ({
    profileImage:
      "https://www.pngitem.com/pimgs/b/156-1569018_jack-sparrow-png.png",
  }),
};
</script>
