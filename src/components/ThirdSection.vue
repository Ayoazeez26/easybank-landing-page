<template>
  <div class="thirdSection w-full">
    <div class="section-content flex flex-col h-full justify-start md:justify-between items-center md:items-start pb-20 w-full">
      <div class="second-desc mb-10 mt-10 md:mt-24 text-center md:text-left w-9/10">
        <h1 class="text-4xl md:text-5xl leading-tight mb-6 md:mb-8">Latest Articles</h1>
      </div>
      <div class="content-list second-desc flex flex-col md:flex-row h-full justify-start md:justify-between items-center md:items-start w-9/10 md:w-full">
        <div class="content-item item-1 flex flex-col items-center md:items-start text-left mb-6">
          <img src="../assets/images/image-currency.jpg" class="rounded-t-lg" alt="currency-image">
          <div class="content-content rounded-b-lg bg-white px-5 py-8">
            <p class="author text-xs md:text-sm">By Claire Robinson</p>
            <h2 class="text-xl md:text-2xl leading-none mb-4 mt-6 w-full">Receive money in any currency with no fees</h2>
            <p class="text-base md:text-lg leading-tight">The world is getting smaller and we’re becoming more mobile. So why should you be forced to only receive money in a single …</p>
          </div>
        </div>
        <div class="content-item item-1 flex flex-col items-center md:items-start text-left mb-6">
          <img src="../assets/images/image-restaurant.jpg" class="rounded-t-lg" alt="restaurant-image">
          <div class="content-content rounded-b-lg bg-white px-5 py-8">
            <p class="author text-xs md:text-sm">By Wilson Hutton</p>
            <h2 class="text-xl md:text-2xl leading-none mb-4 mt-6 w-full">Treat yourself without worrying about money</h2>
            <p class="text-base md:text-lg leading-tight">Our simple budgeting feature allows you to separate out your spending and set realistic limits each month. That means you …</p>
          </div>
        </div>
        <div class="content-item item-1 flex flex-col items-center md:items-start text-left mb-6">
          <img src="../assets/images/image-plane.jpg" class="rounded-t-lg" alt="airplane-image">
          <div class="content-content rounded-b-lg bg-white px-5 py-8">
            <p class="author text-xs md:text-sm">By Wilson Hutton</p>
            <h2 class="text-xl md:text-2xl leading-none mb-4 mt-6 w-full">Take your Easybank card wherever you go</h2>
            <p class="text-base md:text-lg leading-tight">We want you to enjoy your travels. This is why we don’t charge any fees on purchases while you’re abroad. We’ll even show you …</p>
          </div>
        </div>
        <div class="content-item item-1 flex flex-col items-center md:items-start text-left mb-6">
          <img src="../assets/images/image-confetti.jpg" class="rounded-t-lg" alt="confetti-image">
          <div class="content-content rounded-b-lg bg-white px-5 py-8">
            <p class="author text-xs md:text-sm">By Claire Robinson</p>
            <h2 class="text-xl md:text-2xl leading-none mb-4 mt-6 w-full">Our invite-only Beta accounts are now live!</h2>
            <p class="text-base md:text-lg leading-tight">After a lot of hard work by the whole team, we’re excited to launch our closed beta. It’s easy to request an invite through the site ...</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ThirdSection"
}
</script>

<style scoped>
.thirdSection {
  background-color: #FAFAFA;
}
.section-content {
  width: 100%;
  max-width: 1280px;
  margin: 0 auto;
}
.invite-btn {
  background: rgb(49,211,92);
  background: linear-gradient(90deg, rgba(49,211,92,1) 0%, rgba(43,183,218,1) 100%);
  border-radius: 30px;
}
.invite-btn:hover {
  cursor: pointer;
  background: rgb(30,228,82);
  background: linear-gradient(90deg, rgba(30,228,82,1) 0%, rgba(24,200,208,1) 100%);
}
.second-desc h1,
.second-desc h3 {
  color: #2D314D;
}
.second-desc p {
  color: #9698A6;
}
.phones {
  top: -54px;
  background: url('../assets/images/bg-intro-desktop.svg');
  background-position: bottom left;
}
.image-mockup {
  margin-left: 18%;
}
.random-container {
  overflow-x: hidden;
}
.content-item img {
  height: 226px;
}
@media screen and (min-width: 768px) { 
  .content-item {
    width: 23.5%;
  }
}
</style>