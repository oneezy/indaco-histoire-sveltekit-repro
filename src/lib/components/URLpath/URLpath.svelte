<script>
  import { page } from '$app/stores'
</script>

<div class="h-screen w-full flex flex-col items-center justify-center">
  <p class="text-xl">You're on page...</p>
  <h1 class="text-center text-9xl font-bold">{$page.url.pathname}</h1>
</div>