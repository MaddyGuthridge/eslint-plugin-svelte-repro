<script lang="ts">
  type Props = {
    children: import('svelte').Snippet,
  }

  const { children }: Props = $props();
</script>

{@render children()}
