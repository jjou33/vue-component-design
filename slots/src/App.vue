<template>
  <div>
    <ul>
      <item>
        아이템 1
      </item>
      <item>
        아이템 2
        <button>Click</button>
      </item>
      <item>
        아이템 3
        <img src="./assets/testImg.jpg" alt="테스트 이미지" width="50px" />
      </item>
    </ul>
  </div>
</template>

<script>
import Item from "./Item.vue";

export default {
  components: {
    Item,
  },
};
</script>
