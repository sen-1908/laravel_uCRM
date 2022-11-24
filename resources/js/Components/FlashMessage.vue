<script setup>

</script>

<template>
    <p>{{$page.props.flash.status}}</p>
    <div v-if="$page.props.flash.status === 'success'" class="bg-blue-300 text-white p4">
        {{$page.props.flash.message}}
    </div>
</template>