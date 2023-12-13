<template>
    <div class="kb-c4-wrap">
        <div class="kb-c4-h2-wrap">
            <h2 class="kb-c4-h2">Sifatsiz</h2>
        </div>
        <div class="kb-c4-area"><Card /><Card /><Card /></div>
    </div>
</template>

<script>
import Card from "../components/Card.vue";
export default {
    components: {
        Card,
    },
};
</script>

<style>
.kb-c4-wrap {
    display: flex;
    flex-direction: column;
    max-width: 350px;
    width: 100%;
    row-gap: 20px;
}
.kb-c4-h2 {
    color: white;
    font-size: 15px;
}
.kb-c4-h2-wrap {
    background-color: red;
    display: grid;
    place-content: center;
    border-radius: 5px;
}
.kb-c4-area {
    display: flex;
    flex-direction: column;
    background-color: rgba(242, 72, 33, 0.4);
    min-height: 400px;
    padding: 15px;
    row-gap: 15px;
    border-radius: 5px;
}
</style>
