<template>
  <div class="container">
    <div class="content">
      <header class="header">
        <div class="wrapper">
          <ul class="header-menu">
            <li>
              <nuxt-link to="/">
                Home
              </nuxt-link>
            </li>
            <li>
              <nuxt-link to="aboutUs">
                About Us
              </nuxt-link>
            </li>
          </ul>
        </div>
      </header>
      <Nuxt class="wrapper" />
    </div>
    <footer class="footer">
      <h3>Contact us</h3>
      <div>
        <div>
          <ul>
            <li>
              <b>Email</b><br>
              needhelp@organick.com
            </li>
            <li>
              <b>Phone</b><br>
              123 (1254) 1452
            </li>
            <li>
              <b>Adress</b><br>
              88 Road, Brooklyn Street, USA
            </li>
          </ul>
        </div>
      </div>
      <div>Copyright © 2022 | All rights reserved.</div>
    </footer>
  </div>
</template>

<script>
</script>
