<template>
  <div>
    <h1 class="text-2xl">{{ msg }}</h1>
    <button
      class="bg-blue-500 hover:bg-blue-700 text-white py-2 px-4 my-4 rounded"
      @click="count++">
      count is: {{ count }}
    </button>
    <p>
      Edit <code class="bg-gray-200 text-sm p-1 rounded">components/HelloWorld.vue</code> to test hot module replacement.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
