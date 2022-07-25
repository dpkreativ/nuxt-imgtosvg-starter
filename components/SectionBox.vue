<template>
  <section>
    <article
      class="h-64 w-full bg-gray-200 rounded-lg p-5 relative overflow-hidden"
    >
      <slot name="article" />
    </article>

    <div class="w-full flex flex-row-reverse justify-between my-5">
      <slot name="buttons" />
    </div>
  </section>
</template>
