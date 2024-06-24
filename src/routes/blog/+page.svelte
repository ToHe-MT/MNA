<script>
  import { formatDateToIndonesian } from "$lib/function/format.js";
  export let data;
</script>

<div
  class="hero relative flex items-center justify-center w-full bg-cover bg-center bg-white py-10"
>
  <div class="container mx-auto p-6 flex flex-col gap-8">
    <div
      class="text-black flex flex-col justify-center items-center text-center gap-2"
    >
      <h3 class="text-center text-lg md:text-xl text-blue-700">Blog</h3>
      <h1
        class="text-center text-2xl md:text-4xl font-semibold tracking-wide text-black"
      >
        Artikel-Artikel MNA Travel
      </h1>
    </div>
    <div
      class="grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-3 gap-4 md:px-0 lg:px-12"
    >
      {#if data.blog && data.blog.length > 0}
        {#each data.blog as item}
          <div class="rounded-xl shadow-md drop-shadow flex flex-col">
            <div>
              {#if item.images && item.images.length > 0}
                <img
                  src="{import.meta.env.VITE_S3_PUBLIC_URL}/blog/{item.images[0]
                    .picture_id}"
                  alt=""
                  class="rounded-t-xl w-full h-auto"
                />
              {:else}
                <img src="/Sementara.jpg" alt="" class="rounded-t-xl" />
              {/if}
            </div>

            <div class="flex flex-col p-5 gap-1 h-full justify-between">
              <p class="text-xs font-thin">
                {formatDateToIndonesian(item.created_at)}
              </p>
              <h1 class="text-sm font-semibold">{item.title}</h1>
              <a
                href="/blog/{item.slug}"
                class="text-blue-700 text-xs self-end items-end"
              >
                Baca Selengkapnya -></a
              >
            </div>
          </div>
        {/each}
      {/if}
      <div></div>
    </div>
  </div>
</div>

<style>
  /* Adding some custom shadow for testing */
  .custom-shadow {
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
</style>
