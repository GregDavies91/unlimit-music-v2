<template>
  <div class="scene">
    <div class="noticeboard">
      <div class="poster logo-poster"><img src="/logo.svg" alt="Unlimit Music" /></div>
      <a href="/chords/" target="_blank" rel="noopener" class="poster"><span>Songwriting<br/>Tool</span></a>
      <div class="poster"><span>Indie Rock<br/>Trip Hop</span></div>
      <div class="poster"><span>info@<br/>unlimitmusic.com</span></div>
      <div class="poster"><span>demos@<br/>unlimitmusic.com</span></div>
    </div>
    <a href="/simplisticscientists/" target="_blank" rel="noopener" class="door">
      <div class="door-photo"><img src="/assets/artists/smplstcscntsts.jpg" alt="Simplistic Scientists" /></div>
      <div class="sticky">Exploring sound, space &amp; the metaverse.</div>
      <div class="door-handle">Enter Studio →</div>
    </a>
  </div>
</template>

<script setup>
const _v = 'v8'
</script>

<style scoped>
.scene { height: 100vh; width: 100%; display: flex; align-items: center; justify-content: center; gap: 4rem; background: #1a1a1a; font-family: 'Inter', system-ui, sans-serif; flex-wrap: wrap; padding: 2rem; box-sizing: border-box; margin: 0; }
.noticeboard { background: #c9a96e; border: 6px solid #8b6f47; border-radius: 4px; padding: 20px; width: 280px; box-shadow: 4px 4px 12px #0008; display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
.poster { background: #fff; padding: 8px; border-radius: 2px; box-shadow: 2px 2px 6px #0004; text-align: center; font-family: 'Space Mono', monospace; font-size: 11px; min-height: 80px; display: flex; align-items: center; justify-content: center; color: #333; text-transform: uppercase; letter-spacing: .05em; text-decoration: none; }
.poster.logo-poster { grid-column: 1 / -1; }
.poster.logo-poster img { height: 36px; }
.door { background: #5a3825; border: 8px solid #3e2723; border-radius: 4px; width: 280px; padding: 24px; box-shadow: 4px 4px 12px #0008; display: flex; flex-direction: column; align-items: center; gap: 16px; text-decoration: none; color: #fff; }
.door-photo { width: 100%; aspect-ratio: 4/3; overflow: hidden; border: 4px solid #3e2723; }
.door-photo img { width: 100%; height: 100%; object-fit: cover; }
.sticky { background: #fff9c4; color: #333; padding: 10px 14px; border-radius: 2px; box-shadow: 2px 2px 6px #0004; font-family: 'Space Mono', monospace; font-size: 12px; transform: rotate(-2deg); }
.door-handle { background: #6366f1; border: none; border-radius: 8px; padding: 10px 20px; font-size: 14px; font-weight: 600; color: #fff; width: 100%; text-align: center; }
@media (max-width: 700px) { .scene { flex-direction: column; } }
</style>
