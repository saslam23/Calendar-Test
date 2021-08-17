<template>
  <div class="hello">
    <div title="Add to Calendar" class="addeventatc">
    Add to Calendar
    <span class="start">08/31/2021 08:00 AM</span>
    <span class="end">08/31/2021 10:00 AM</span>
    <span class="timezone">America/Los_Angeles</span>
    <span class="title">Test Event</span>
    <span class="description">This is a description of the test event</span>
    <span class="location">Location of the TEST event. We will go to test land on this date and book a testcation!</span>
</div>
    </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
