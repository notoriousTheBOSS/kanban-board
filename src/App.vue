<template>
    <div class="container">
        <div class="kb-wrapper">
            <div class="kb-wrapper-header">
                <span></span>
                <button class="add-btn">+ Yangi qo'shish</button>
            </div>
            <div class="kb-wrapper-board">
                <Yangi />
                <Amalda />
                <Kutiluvchi />
                <Sifatsiz />
                <Sifatli />
            </div>
        </div>
    </div>
</template>

<script>
import Amalda from "./components/Amalda.vue";
import Kutiluvchi from "./components/Kutiluvchi.vue";
import Sifatli from "./components/Sifatli.vue";
import Sifatsiz from "./components/Sifatsiz.vue";
import Yangi from "./components/Yangi.vue";
export default {
    components: {
        Yangi,
        Amalda,
        Kutiluvchi,
        Sifatli,
        Sifatsiz,
    },
};
</script>
<style>
.container {
    max-width: 100vw;
    margin: 0 auto;
    padding: 0 10px;
}
.kb-wrapper-header {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 50px 0;
}
.kb-wrapper-board {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    row-gap: 30px;
}
.add-btn {
    max-width: 200px;
    width: 100%;
    color: white;
    border: 3px solid rgb(3, 139, 3);
    background: #14ae5c;
    padding: 10px 0;
    border-radius: 6px;
}
</style>
