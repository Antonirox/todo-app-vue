<template>
    <div id="app" class="bg-fixed" style="background-image: url(https://previews.123rf.com/images/sanek13744/sanek137441712/sanek13744171200457/92330417-para-hacer-una-lista-de-fondo-sin-patr%C3%B3n-ilustraci%C3%B3n-de-vector-plano-de-negocios-lista-de-verificaci%C3%B3n-patr%C3%B3n-de.jpg)">
        <TodoList/>
    </div>
</template>

<script>
import TodoList from './components/TodoList.vue'

export default {
    name: 'app',
    components: {
        TodoList
    }
}
</script>