<template>
  <footer
    v-if="$slidev.nav.currentPage !== 8 && $slidev.nav.currentPage !== $slidev.nav.total"
    class="common-footer"
  >
    <span>
      Agentic AI Melbourne ·
      2 September 2026 ·
      Ryan Djurovich ·
      <a href="https://aimelb.org">aimelb.org</a>
    </span>
    <span class="footer-meta">
      {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
    </span>
  </footer>
</template>
