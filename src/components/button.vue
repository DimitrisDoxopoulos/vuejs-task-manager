<!-- ----------------- Templates --------------- -->

<template>
    <button :style="{background: color}" class="btn" @click='onClick()'>{{ text }}</button>
</template>
    
<!-- ----------------- Templates --------------- -->

<!-- ----------------- Scipts --------------- -->
<script>

    export default
    {
        name: 'Button',
        props: {
            text: String,
            color: String
        },
        methods: {
            onClick() {
                this.$emit('btn-click')
            },
        }
    
    }
</script>

<!-- -------x--------- Scipts --------x------- -->

<!-- ----------------- Styles --------------- -->



<!-- ------x--------- Styles --------x----- -->