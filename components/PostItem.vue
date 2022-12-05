<template>
  <div class="post-container py-8">
    <h3 class="text-3xl font-bold">
      <NuxtLink :to="`/posts/1`">Title of Post</NuxtLink>
    </h3>
    <div class="post-meta text-gray-700 flex items-center space-x-2">
      <div>Dec 4, 2022</div>
      <div>&middot;</div>
      <div>Drashtant nayak</div>
    </div>
    <div class="post-preview leading-relaxed mt-4">
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci amet asperiores, assumenda commodi ea exercitationem facere, illo illum in iste nisi officiis placeat quos ratione reiciendis reprehenderit tempora tempore unde? Accusamus alias cupiditate deleniti doloribus eum reiciendis saepe voluptas voluptates.
    </div>
    <div class="mt-4">
      <NuxtLink :to="`/posts/1`" class="bg-blue-700 hover:bg-blue-800 text-white rounded inline-block px-4 py-2">
        Read More
      </NuxtLink>
    </div>
  </div>
</template>