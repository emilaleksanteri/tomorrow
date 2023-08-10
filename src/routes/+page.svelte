<script lang="ts">
import { Confetti } from "svelte-confetti"
import DiscordLogo from "$lib/discord-logo-blue.svg?raw"

</script>
<main class="w-screen h-screen flex items-center justify-center relative flex-col bg-zinc-800">
  <div class="abosulte z-10">
    <Confetti size={40} x={[-1, 1]} y={[-1, 1]} fallDistance={800} xSpread={0.02} delay={[0, 100]} iterationCount={5} />
  </div>
  <h1 class="font-bold text-6xl text-white underline decoration-[#5865F2] mb-8 mt-8">Tomorrow</h1>
  <p class="text-zinc-500 font-thin">By the milk group <span class="text-xs font-thin">Tm</span></p>
  <div class="w-32 h-32 mt-4">
    <a class="w-32 h-32" href="https://discord.gg/qtn6vnr4">
      {@html DiscordLogo}
    </a>
  </div>
</main>

