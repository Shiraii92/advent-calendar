<template>
  <Day day="05.12.2022">
    <div slot="page-content">
      <h3>Raffle Day</h3>
      <p class = textbox>
       Ahoi, landlubbers! To participate in the todays <font size= "6"><b>Giveaway</b></font> simply do the following tasks:
        <ul>
        <li><div class=link>Click this &nbsp; <a href="https://wichtelmania.com/g/BAQ4jX5ng6zWJ3" target="_blank">  <b>Link</b> </a> </div></li>
        <li>Register with your Twitter or Telegram handle</li>
       </ul>
       
      </p>
      <div class =logo>
      <img
        width="300"
        src="https://talkaboat.online/assets/images/talkaboat_light.png"
        alt=""
     />
     </div>
    </div>
  </Day>
</template>

<script>
import Day from "../Day.vue";

export default {
  name: "Day01",
  components: {
    Day,
  },
};
</script>

<style lang="scss" scoped>

h1 {
    font-size: 6rem;
    text-shadow: 0 2px 8px #666;
    padding-top: 1;
    margin: 5px;

  }

.link {
    display: flex;
    justify-content: block;
    font-size: 14px;
    z-index: 500;

    

    a {
      color: rgb(95,141,62);
      z-index: 500;
    }
  }

  .logo {
    display: flex;
    justify-content: center;
    font-size: 14px;
    z-index: 500;

    

    a {
      z-index: 500;
    }
  }  
</style>