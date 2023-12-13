<template>
    <div class="kb-c3-wrap">
        <div class="kb-c3-h2-wrap">
            <h2 class="kb-c3-h2">Kutiluvchi</h2>
        </div>
        <div class="kb-c3-area"><Card /></div>
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
.kb-c3-wrap {
    display: flex;
    flex-direction: column;
    max-width: 350px;
    width: 100%;
    row-gap: 20px;
}
.kb-c3-h2 {
    color: black;
    font-size: 15px;
}
.kb-c3-h2-wrap {
    background-color: rgb(231, 151, 3);
    display: grid;
    place-content: center;
    border-radius: 5px;
}
.kb-c3-area {
    display: flex;
    flex-direction: column;
    background-color: rgba(255, 166, 41, 0.6);
    min-height: 400px;
    padding: 15px;
    row-gap: 15px;
    border-radius: 5px;
}
</style>
