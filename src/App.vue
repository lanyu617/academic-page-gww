<template>
  <div id="wrapper">
    <header id="header" :class="{ alt: isHome }">
      <RouterLink to="/" class="logo"><strong>BUCT</strong> <span>Gu Weiwei</span></RouterLink>
      <nav>
        <a href="#menu" @click.prevent="toggleMenu">Menu</a>
      </nav>
    </header>

    <nav id="menu" :class="{ open: menuOpen }">
      <ul class="links">
        <li><RouterLink to="/" @click="closeMenu">HOME</RouterLink></li>
        <li><RouterLink to="/publications" @click="closeMenu">PUBLICATIONS</RouterLink></li>
        <li><RouterLink to="/students" @click="closeMenu">STUDENTS</RouterLink></li>
      </ul>
    </nav>

    <RouterView />

    <footer id="footer">
      <div class="inner">
        <ul class="copyright">
          <li>&copy; Untitled</li>
          <li>Design: <a href="https://html5up.net">HTML5 UP</a></li>
        </ul>
      </div>
    </footer>
  </div>
</template>

<script setup>
import { ref, computed } from 'vue'
import { useRoute, RouterLink, RouterView } from 'vue-router'

const menuOpen = ref(false)
const route = useRoute()

const isHome = computed(() => route.path === '/')

function toggleMenu() {
  menuOpen.value = !menuOpen.value
}
function closeMenu() {
  menuOpen.value = false
}
</script>

<style scoped>
#menu {
  display: none;
}
#menu.open {
  display: block;
}
</style>
