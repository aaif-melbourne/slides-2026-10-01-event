<template>
  <footer
    v-if="![7, 9, 14, $slidev.nav.total].includes($slidev.nav.currentPage)"
    class="common-footer"
  >
    <span>
      Agentic AI Melbourne ·
      1 October 2026 ·
      Gajan Kugamoorthy ·
      <a href="https://aimelb.org">aimelb.org</a>
    </span>
    <span class="footer-meta">
      {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
    </span>
  </footer>
</template>
