<template>
    <div class="about">
        <h1>Hello {{name}}, This is an about page</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Exercitationem animi iure voluptate, facilis reiciendis amet nobis omnis obcaecati reprehenderit eligendi dolorem explicabo impedit molestias pariatur et modi a! Unde, facilis.</p>
    </div>
</template>

<script>
export default {
    name: 'About',
    data() {
        return {
            name: this.$route.params.name
        }
    }
}
</script>