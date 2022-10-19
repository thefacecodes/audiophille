<template>
  <footer>
    <div class="top">
      <img src="../assets/shared/desktop/logo.svg" alt="" />
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/">Headphones</router-link></li>
        <li><router-link to="/">Speaker</router-link></li>
        <li><router-link to="/">Earphones</router-link></li>
      </ul>
    </div>
    <div class="below">
      <div class="details">
        <p>
          Audiophile is an all in one stop to fulfill your audio needs. We're a small team
          of music lovers and sound specialists who are devoted to helping you get the
          most out of personal audio. Come and visit our demo facility - we’re open 7 days
          a week.
        </p>

        <p>&copy; Copyright 2022. All Rights Reserved</p>
      </div>
      <div class="socials">
        <i class="fa-brands fa-square-facebook"></i>
        <i class="fa-brands fa-twitter"></i>
        <i class="fa-brands fa-instagram"></i>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>

<style scoped>
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css");
footer {
  background: black;
  color: #808080;
  padding: 5em 15em;
}

.top {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.top ul li {
  display: inline;
  text-transform: uppercase;
  padding: 2em;
  font-size: 1.3em;
  font-weight: 700;
}

a {
  text-decoration: none;
  color: white;
}

.below {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 1em;
  font-size: 1.3em;
}

.details,
.socials {
  width: 50%;
}

.details p {
  margin-top: 3em;
}

.socials {
  font-size: 2.5em;
  color: white;
  text-align: right;
}

.socials i {
  margin-right: 0.5em;
}

@media (max-width: 480px) {
  footer {
    padding: 20px;
  }

  .top,
  .below {
    width: 100%;
    flex-direction: column;
    gap: 20px;
    justify-content: unset;
    align-items: flex-start;
    margin-top: unset;
  }

  .top ul li {
    display: block;
    padding: unset;
    padding-block: 10px;
  }

  .details,
  .socials {
    width: 100%;
    text-align: unset;
    /* margin-block: 10px; */
  }
}
</style>
