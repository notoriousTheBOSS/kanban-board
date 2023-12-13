<template>
    <div class="kb-c1-wrap">
        <div class="kb-c1-h2-wrap">
            <h2 class="kb-c1-h2">Yangi</h2>
        </div>
        <div class="kb-c1-area"><Card /></div>
    </div>
</template>

<script>
import Card from "./Card.vue";
export default {
    components: {
        Card,
    },
};
</script>

<style>
.kb-c1-wrap {
    display: flex;
    flex-direction: column;
    max-width: 350px;
    width: 100%;
    row-gap: 20px;
}
.kb-c1-h2 {
    font-size: 15px;
}
.kb-c1-h2-wrap {
    background-color: rgb(94, 93, 93);
    display: grid;
    place-content: center;
    color: white;
    border-radius: 5px;
}
.kb-c1-area {
    display: flex;
    flex-direction: column;
    background-color: rgb(228, 228, 228);
    min-height: 400px;
    padding: 15px;
    row-gap: 15px;
    border-radius: 5px;
}
</style>
