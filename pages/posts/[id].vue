<template>
  <div class="container mx-auto w-1/2 py-8">
    <Title>{{ $route.params.id }} | {{ title }}</Title>
    <div class="post-container py-8">
      <h3 class="text-3xl font-bold">
        <NuxtLink :to="`/posts/1`">Title of Post</NuxtLink>
      </h3>
      <div class="post-meta text-gray-700 flex items-center space-x-2">
        <div>Dec 4, 2022</div>
        <div>&middot;</div>
        <div>Drashtant nayak</div>
      </div>
      <div class="post-content mt-7">
        {{ $route.params.id }} Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus assumenda,
        consequatur
        consequuntur exercitationem explicabo fuga hic, iste iusto minima nam necessitatibus numquam optio placeat
        possimus
        quo repellendus sapiente temporibus voluptates?
      </div>
    </div>
  </div>
</template>
<script setup>
const title = useState('title')
</script>