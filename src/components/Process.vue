<template>
  <h2>We specialise in:</h2>
  <div class="cards">
    <div class="card">
      <h3>Innovative web solutions</h3>
      <p>
        We assist you right from the concept stage via design and development
        right to the 24/7 operation of your software. Our solutions are
        characterised by their great scalability, security, performance, user
        friendly interface design and seamless integration into your existing
        system landscape. The implementation is done using state-of-the-art
        technologies and various content management systems.
      </p>
    </div>

    <div class="card">
      <h3>Smart web shops</h3>
      <p>
        design and implementation of E-Commerce solutions for an individual
        purchasing experience that is state-of-the-art. We specialise in the
        implementation of complex web shop solutions for the B2B and B2C sector
        using our standard modules PIM (Product Information Management), CRM
        (Customer Relationship Management), web shop and payment. On request, we
        can also optimise your E-Commerce solution as an app for smartphone and
        tablet.
      </p>
    </div>
    <div class="card">
      <h3>Mobile solutions</h3>
      <p>
        Smartphone and tablets have become an integral part of everyday life. In
        many cases they are the mobile distribution channels for product search
        and product purchasing. Competitive companies have to also be available
        on those mobile terminals. Lemon42 specialises in the development of
        apps. It does not matter if you want a tailor-made company solution or
        an innovative sector solution, we deliver our products as native apps,
        hybrid apps or web apps.
      </p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  justify-content: center;
}
</style>
