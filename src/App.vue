<script setup>

</script>

<template>
    <header>
        <nav class="navbar navhatter bg-body-tertiary">
            <div class="container-fluid d-flex justify-content-between">
                <div>
                    <a class="navbar-brand">Harmónia</a>
                </div>
                
                <div class=" d-flex gap-4">
                    <a href="">Szobák</a>
                    <a href="">Foglalások</a>
                    <a href="" class="ujFoglalas">+ Új Foglalás</a>
                </div>
            </div>
        </nav>

        <div class="d-flex justify-content-between">
            <div>

            </div>

            <div class="infok">

            </div>
        </div>

    </header>
</template>

<style scoped>

.navhatter {
    background-color: #153F36 !important;
    padding-top: 15px;
    padding-bottom: 15px;
}

a {
    color: #fff;
    text-decoration: none;
}

.ujFoglalas {
    background-color: #fff;
    padding: 5px;
    color: #000;
    border-radius: 5px;
}

</style>