<template>
  <section class="about">
    <div class="left">
      
    </div>
    <div class="right">
      <div class="text">
        <p class="title">
          Lorem ipsum amet Lorem
        </p>
        <p class="body">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit.
           Perferendis, dignissimos illum soluta velit ratione quaerat
            nisi nostrum corrupti laudantium harum eveniet quasi.
           Officiis fuga maiores saepe nulla? Quasi, delectus cum.
           Lorem ipsum dolor sit, amet consectetur adipisicing elit.
           Perferendis, dignissimos illum soluta velit ratione quaerat
            nisi nostrum corrupti laudantium harum eveniet quasi.
           Officiis fuga maiores saepe nulla? Quasi, delectus cum.
        </p>
        <p class="body mb-3">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit.
           Perferendis, dignissimos illum soluta velit ratione quaerat
            nisi nostrum corrupti laudantium harum eveniet quasi.
           Officiis fuga maiores saepe nulla? Quasi, delectus cum.  
        </p>
        <a href="#" class="read-more">Read More</a>
      </div>
      <div class="gift">
        <img src="img/gifts.png" alt="gifts">
      </div>
      <div class="icons">
        <div class="search">
          <i class="fas fa-search"></i>
        </div>
        <div class="social">
          <i class="fab fa-facebook-square"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-twitter"></i>
        </div>
      </div>
      <div class="message">
        <img src="img/msg.jpg" alt="message icon">
        <p>Talk to us</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  layout: 'app',
  mounted() {
    const nav = document.querySelector('.main-nav');
    nav.classList.add('text-primary');
  }
}
</script>

