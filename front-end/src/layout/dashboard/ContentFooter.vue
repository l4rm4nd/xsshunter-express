<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link">
            <i>NOTICE: Use contextually-aware output encoding. Only <b>you</b> can prevent payload fires.</i>
          </a>
        </li>
      </ul>
      <div class="copyright">
        © {{year}} by <a href="https://github.com/l4rm4nd" target="_blank"><code>LRVT</code></a>
      </div>
    </div>
  </footer>
</template>
<script>
  export default {
    data() {
      return {
        year: new Date().getFullYear()
      }
    }
  };
</script>
<style>
</style>
