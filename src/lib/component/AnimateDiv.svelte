<script>
  import { inview } from "svelte-inview";
  let isInView = false;
  const options = {
    rootMargin: "-70px",
    unobserveOnEnter: true,
  };

  export let className;
  export let beforeAnimated = "opacity-0 translate-y-48"
  export let afterAnimated = "opacity-100 translate-y-0";

  export let delay = "delay-0";
  export let duration = "duration-700";
  export let transitionTiming = "ease-in-out";
  

</script>

<div
  class={`${className} transition-all ${delay} ${duration} ${transitionTiming} ${isInView ? afterAnimated : beforeAnimated}`}
  use:inview={options}
  on:inview_enter={(event) => {
    const { inView } = event.detail;
    isInView = inView;
  }}
>
  <slot />
</div>
