<template>
    <div>
        <img :src=food.image width="198" height="180">
        <div class="card-content">
            <h1 class="text-primary">{{ food.name }}</h1>
            <p>{{ food.description }}</p>
            <p>
                <small>
                    <b>Delicousness:</b>
                </small>
                <b class="text-primary">
                    {{ food.deliciousness }}
                </b>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    props: ['food']
}
</script>

<style>
</style>