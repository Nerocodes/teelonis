<template>
  <section class="stories">
    <div class="left">
      
    </div>
    <div class="right">
      <div class="flex">
        <div class="text">
          <p class="title">
            Adenike Fola
          </p>
          <p class="bio">
            Ceo mayers vision scope enterprise
            <br>
            lorem ipsum loremipsum
          </p>
          <p class="featured">
            <i class="far fa-star"></i>
            Featured story
          </p>
          <p class="body">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Perferendis, dignissimos illum soluta velit ratione quaerat
              nisi nostrum corrupti laudantium harum eveniet quasi.
            Officiis fuga maiores saepe nulla? Quasi, delectus cum.
            Lorem ipsum dolor sit, amet consectetur adipisicing elit.
          </p>
          <p class="body mb-3">
            Perferendis, dignissimos illum soluta velit ratione quaerat
              nisi nostrum corrupti laudantium harum eveniet quasi.
            Officiis fuga maiores saepe nulla? Quasi, delectus cum.
            Lorem ipsum dolor sit, amet consectetur adipisicing elit.
            Perferendis, dignissimos illum soluta velit ratione quaerat
              nisi nostrum corrupti laudantium harum eveniet quasi.
            Officiis fuga maiores saepe nulla? Quasi, delectus cum.  
          </p>
          <a href="#" class="read-more">Read More</a>
        </div>
        <div class="image">
          <img src="img/sit.jpg" alt="gifts">
        </div>
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