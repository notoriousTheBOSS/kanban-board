<template>
    <div class="kb-c2-wrap">
        <div class="kb-c2-h2-wrap">
            <h2 class="kb-c2-h2">Amalda</h2>
        </div>
        <div class="kb-c2-area"><Card /><Card /></div>
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
.kb-c2-wrap {
    display: flex;
    flex-direction: column;
    max-width: 350px;
    width: 100%;
    row-gap: 20px;
}
.kb-c2-h2 {
    font-size: 15px;
}
.kb-c2-h2-wrap {
    background-color: #ffcd29;
    display: grid;
    place-content: center;
    color: black;
    border-radius: 5px;
}
.kb-c2-area {
    display: flex;
    flex-direction: column;
    background-color: rgba(255, 205, 41, 0.4);
    min-height: 400px;
    padding: 15px;
    row-gap: 15px;
    border-radius: 5px;
}
</style>
