<template>
    <div class="container mx-auto px-4 py-20 flex flex-col flex-wrap">
        <h1 class="font-hairline text-6xl text-center text-black-500">Cyber Link</h1>

        <todo-card class="mx-auto mt-4 h-64 w-full max-w-lg">
            Todo List
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="Title" type="text" placeholder="Title">
            <input class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" id="Name" type="text" placeholder="Name">
        <label class="block text-gray-700 text-sm font-bold mb-2" for="username">
        Did you finish your task?
      </label>
      <button class="bg-green-500 hover:bg-green-400 text-white font-bold py-2 px-4 border-b-4 border-green-700 hover:border-green-500 rounded">
  Yes
</button>
<button class="bg-red-500 hover:bg-red-400 text-white font-bold py-2 px-4 border-b-4 border-red-700 hover:border-red-500 rounded">
  No
</button>
        </todo-card>
        <todo-card class="mx-auto mt-10 w-full max-w-lg">
            <button class="bg-green-600 hover:bg-green-400 text-white font-bold py-2 px-4 border-b-4 border-green-500 hover:border-green-300 rounded">
            Create
            </button> 
            <button class="bg-blue-600 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-500 hover:border-blue-300 rounded">
            View
             </button> 
             <button class="bg-orange-600 hover:bg-orange-400 text-white font-bold py-2 px-4 border-b-4 border-orange-500 hover:border-orange-300 rounded">
            Edit
             </button> 
             <button class="bg-red-600 hover:bg-red-400 text-white font-bold py-2 px-4 border-b-4 border-red-500 hover:border-red-300 rounded">
            Eliminate
             </button> 
        </todo-card>
    </div>
</template>

<script>
export default {
    props: {

    },

    data () {
        return {
            tasks: [
                {
                    id: 1,
                    title: 'Example task',
                    done: false
                }
            ]
        };
    },

    mounted () {

    },

    methods: {

    }
}
</script>