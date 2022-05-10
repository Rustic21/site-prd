<template>    
    <v-app-bar class="cabecalho" color="transparent">
        <div class="container-app-bar">
            <div class="mx-3 brand">
                Nome empresa
            </div>
            <v-spacer></v-spacer>

            <div class="mx-3 item-1">
                menu 1
            </div>

            <div class="mx-3 item-2">
                menu 2
            </div>        
        </div>
    </v-app-bar>
</template>

<script>
</script>

<style lang="scss" scoped>
// .app-bar-custom {
//     z-index: 999;
// }

.cabecalho {
    color: white !important;
    // background-color: black;
}

.container-app-bar {
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 0px 100px;
}

</style>