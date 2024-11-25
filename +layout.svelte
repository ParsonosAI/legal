<script lang="ts">
  import type { Snippet } from "svelte"

  interface Props {
    children?: Snippet
  }

  let { children }: Props = $props()
</script>

<div class="container prose prose-stone mx-auto py-8 lg:prose-lg lg:py-16">
  {@render children?.()}
</div>
