<template>
    <div class="kb-c5-wrap">
        <div class="kb-c5-h2-wrap">
            <h2 class="kb-c5-h2">Sifatli</h2>
        </div>
        <div class="kb-c5-area"><Card /></div>
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
.kb-c5-wrap {
    display: flex;
    flex-direction: column;
    max-width: 350px;
    width: 100%;
    row-gap: 20px;
}
.kb-c5-h2 {
    color: white;
    font-size: 16px;
}
.kb-c5-h2-wrap {
    background-color: #14ae5c;
    display: grid;
    place-content: center;
    border-radius: 5px;
}
.kb-c5-area {
    display: flex;
    flex-direction: column;
    background-color: rgba(20, 173, 92, 0.4);
    min-height: 400px;
    padding: 15px;
    row-gap: 15px;
    border-radius: 5px;
}
</style>
