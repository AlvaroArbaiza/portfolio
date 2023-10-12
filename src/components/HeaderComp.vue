<script>
    export default {
        name: 'HeaderComp',
        data() {
            return {
                
            }
        }
    }
</script>

<template>
    <header class="container-fluid">
        <div class="container">

            <h2 class="text-danger">Header</h2>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../style/main.scss';

header{
    background-color: aqua;
}
</style>
