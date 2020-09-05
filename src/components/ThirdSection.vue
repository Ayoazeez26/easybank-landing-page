<template>
  <div class="thirdSection w-full">
    <div class="section-content flex flex-col h-full justify-start md:justify-between items-center md:items-start w-full">
      <div class="second-desc mb-10 mt-10 md:mt-24 text-center md:text-left w-11/12">
        <h1 class="text-4xl md:text-5xl leading-tight mb-6 md:mb-8">Latest Articles</h1>
      </div>
      <div class="content-list second-desc flex flex-col md:flex-row h-full justify-start md:justify-between items-center md:items-start w-full">
        <div class="content-item item-1 flex flex-col items-center md:items-start rounded-lg text-center md:text-left">
          <img src="../assets/images/image-currency.jpg" alt="currency-image">
          <div class="content-content bg-white px-4 py-5">
            <p class="author text-sm">By Claire Robinson</p>
            <h2 class="text-3xl font- mb-4 mt-6">Receive money in any currency with no fees</h2>
            <p class="text-xl mb-8">The world is getting smaller and we’re becoming more mobile. So why should you be forced to only receive money in a single …</p>
          </div>
        </div>
        <div class="content-item item-2 flex flex-col items-center md:items-start text-center md:text-left">
          <img src="../assets/images/icon-budgeting.svg" alt="simple-budgeting-image">
          <h2 class="text-3xl font- mb-4 mt-6">Simple Budgeting</h2>
          <p class="text-xl mb-8">See exactly where your money goes each month. Receive notifications when you’re close to hitting your limits.</p>
        </div>
        <div class="content-item item-3 flex flex-col items-center md:items-start text-center md:text-left">
          <img src="../assets/images/icon-onboarding.svg" alt="fast-onboarding-image">
          <h2 class="text-3xl font- mb-4 mt-6">Fast Onboarding</h2>
          <p class="text-xl mb-8">We don’t do branches. Open your account in minutes online and start taking control of your finances right away.</p>
        </div>
        <div class="content-item item-3 flex flex-col items-center md:items-start text-center md:text-left">
          <img src="../assets/images/icon-api.svg" alt="open-api-image">
          <h2 class="text-3xl font- mb-4 mt-6">Open API</h2>
          <p class="text-xl mb-8">Manage your savings, investments, pension, and much more from one account. Tracking your money has never been easier.</p>
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
.ThirdSection {
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
@media screen and (min-width: 768px) { 
  .content-item {
    width: 23.5%;
  }
}
</style>