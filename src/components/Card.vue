<template>
    <div class="card-wrapper">
        <div class="card-wrapper-info">
            <a class="card-wrapper-info-a" href="">Abbosxon</a>
            <p class="card-wrapper-info-p">12.12.2023</p>
        </div>
        <p class="card-wrapper-p">+998 (90) 000-00-00</p>
    </div>
</template>
<style>
.card-wrapper {
    display: flex;
    height: 100px;
    flex-direction: column;
    justify-content: space-between;
    border: 3px solid rgb(190, 190, 190);
    border-radius: 10px;
    background: white;
    padding: 0 7px;
}
.card-wrapper-info-a {
    color: black;
    text-decoration: underline;
    font-size: 21px;
}
.card-wrapper-info-p {
    color: gray;
}
.card-wrapper-info {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.card-wrapper-p {
    font-size: 11px;
    color: rgb(112, 112, 112);
}
</style>
