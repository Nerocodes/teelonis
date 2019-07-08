<template>
  <section class="say-hello">
    <div class="left">
      
    </div>
    <div class="right">
      <div class="flex">
        <div class="text">
          <p class="title">
            Say Hello
          </p>
          <p class="sub-title">
            Fill in your preference
          </p>
          <p class="write-up">
            Lorem ipsum dolor sit amet consectetur adipisicing elit, sed.
          </p>
          <form>
            <input type="email" id="email" name="email" placeholder="EMAIL">
            <textarea name="preference" id="preference" placeholder="EXPERIENCE PREFERENCE"></textarea>
            <input type="submit" value="ENTER" disabled>
          </form>
        </div>
        <div class="contact">
          <div class="info">
            <div class="icon">
              <i class="fas fa-home"></i>
            </div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi, quasi.</p>
          </div>
          <div class="info">
            <div class="icon">
              <i class="fas fa-envelope"></i>
            </div>
            <p>hello@teelonis.com</p>
          </div>
          <div class="info">
            <div class="icon">
              <i class="fas fa-phone-volume"></i>
            </div>
            <p>
              +234 (0) 234 567 8910
              <br>
              +234 (0) 234 567 8910
            </p>
          </div>
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