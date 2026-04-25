<script lang="ts">
  import type { MediaOutput } from "zebar";
  import { Marquee } from "@selemondev/svelte-marquee";
  import "@selemondev/svelte-marquee/dist/style.css";

  export let media: MediaOutput;
</script>

<div
  class="flex items-center gap-2 h-full"
  style="width: 180px; flex-shrink: 0;"
>
  <!-- Music Icon -->
  <i class="ti ti-music pl-2 text-zb-icon"></i>

  <!-- Song Title: static when idle, marquee when playing -->
  {#if media?.currentSession?.title}
    <Marquee
      fade={true}
      pauseOnHover={true}
      innerClassName="[--duration:10s] [--gap:5rem]"
    >
      <span class="text-sm whitespace-nowrap">
        {media.currentSession.title}
      </span>
    </Marquee>
  {:else}
    <span class="text-sm whitespace-nowrap truncate">
      No song playing bro.
    </span>
  {/if}
</div>
