<template>
    <div :globe="globe">
        <img :src="globe.img" />
        <p style="font-size:14px; margin-top:10px">{{globe.title}}</p>
    </div>
</template>

<script>
export default {
    props: ['globe']
}
</script>

<style>

</style>
