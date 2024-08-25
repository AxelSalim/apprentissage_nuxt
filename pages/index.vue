<!-- <script setup>
    // const { sayHello } = useUtils();
    // sayHello();

    // const { $sayHello } = useNuxtApp();

    // console.log(useNuxtApp());

    definePageMeta({
        middleware: 'auth'
    })
    
</script> -->

<!-- <template>
    <div class="container py-3 mx-auto Main">
        <h1>Hello word</h1>
        <IconsBell />
        <img src="@/assets/images/1.jpg" alt="" />
    </div>
</template> -->

<!-- <template>
    <div class="container py-3 mx-auto Main">
        <h1 class="text-teal-500">Hello Nuxt 3</h1>
    </div>
</template> -->

<!-- Package content -->
<!-- <template>
    <div>
        <ContentDoc />
    </div>
</template> -->


<!-- <script setup lang="ts">
 const counter = useCounter();
</script>

<template>
  <div id="main">
    Counter: {{ counter }}
    <button @click="counter++">+</button>
    <button @click="counter--">-</button>
  </div>
  <Counter id="counter"/>
</template> -->


<script setup>
import { useCounterStore } from '~/stores/myStore';

const store = useCounterStore();

console.log(store);
</script>

<template>
    <div>hello</div>
</template>


