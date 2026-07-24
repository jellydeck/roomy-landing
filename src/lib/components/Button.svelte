<script lang="ts">
  import type { Snippet } from "svelte";
  import type { HTMLButtonAttributes, HTMLAnchorAttributes } from "svelte/elements";

  type Props = (HTMLButtonAttributes | HTMLAnchorAttributes) & {
    href?: string;
    children?: Snippet;
  };

  let { href, children, class: className, ...restProps }: Props = $props();

  const styles = [
    "touch-manipulation hover:cursor-pointer",
    "inline-flex items-center justify-center gap-2",
    "whitespace-nowrap rounded-[8px]",
    "text-lg font-bold",
    "outline-offset-2 focus-visible:outline-2",
    "duration-50 active:duration-100",
    "disabled:pointer-events-none disabled:opacity-60",
    "[&_svg]:pointer-events-none [&_svg]:size-4 [&_svg]:shrink-0",
    "px-4 py-1.5",
    "bg-pink-400 dark:bg-pink-400",
    "text-pink-950 [&_svg]:text-pink-700",
    "border border-px border-pink-400 [--shadow-button-color:var(--color-pink-700)]",
    "hover:bg-pink-400 hover:shadow-button",
    "focus-visible:outline-pink-500 dark:focus-visible:outline-pink-300",
    "backdrop-blur-md",
    "active:translate-[2px] active:shadow-none",
  ].join(" ");
</script>

{#if href}
  <a class="{styles} {className ?? ''}" {href} {...restProps as HTMLAnchorAttributes}>
    {@render children?.()}
  </a>
{:else}
  <button class="{styles} {className ?? ''}" type="button" {...restProps as HTMLButtonAttributes}>
    {@render children?.()}
  </button>
{/if}
