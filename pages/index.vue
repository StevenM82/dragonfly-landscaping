<template>
  <div class="main-body">
    <section class="section">
      <article class="article">
        <img
          class="img-fluid"
          :src="require('static/images/glacial-lake.jpg')"
          alt="a calm glacial lake"
        />
        <p class="lead">
          We are a couple of travelers that have taken the time and put in the
          work to allow us see the world. On our first adventure we traveled by
          plane, by bus and by bus (different sort) over the course of a year
          and a half. Our next adventure brings home a little closer to us while
          we get farther from it.
        </p>
      </article>
      <article class="article">
        <p>
          If we have learned one thing from our adventures, it's this. Make time
          for adventures when and wherever you can. Things <i>WILL</i> go
          sideways. You have to be ready for it, but don't let planning stop you
          from doing.
        </p>
        <p>
          They say that there is more to see in the world than could ever be
          experienced in a lifetime.
        </p>
      </article>
    </section>
  </div>
</template>

<script>
export default {
  name: 'LandingPage',
};
</script>
