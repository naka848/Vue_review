<template>
  <div class="card">
    <div class="card-header">
      {{ TweetObj.tweet_id }}
    </div>
    <div class="card-body">
      <div class="card-text">{{ TweetObj.tweet_body }}</div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line
  name: "Tweet",
  props: {
    TweetObj: Object,
  },
};
</script>