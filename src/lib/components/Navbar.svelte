<script lang="ts">
  import NavLink from './NavLink.svelte';
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-white/80 backdrop-blur-md border-b border-gray-100">
  <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
      <!-- Left: Logo & Links -->
      <div class="flex items-center gap-8">
        <a href="/" class="flex items-center gap-2">
          <!-- Logo -->
          <div class="w-8 h-8 bg-black rounded-lg flex items-center justify-center text-white font-bold text-xs">
            T
          </div>
          <span class="font-bold text-lg">TAAARS!</span>
        </a>
        <div class="hidden md:flex items-center gap-6">
          <NavLink label="Features" />
          <NavLink label="Pricing" />
        </div>
      </div>

      <!-- Right: Actions -->
      <div class="flex items-center gap-4">
        <NavLink label="Login" />
        <a
          href="#"
          class="bg-gray-900 text-white px-4 py-2 rounded-full text-sm font-medium hover:bg-gray-800 transition-colors"
        >
          Start free trial
        </a>
      </div>
    </div>
  </div>
</nav>
