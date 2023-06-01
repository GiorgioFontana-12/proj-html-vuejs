<script >

</script>

<template>
    <header>
        <div class="mainBox">
            <img src="../assets/images/white-logo-2.png" alt="Logo">
            <div class="headerLink">
                <a class="margin1rem" href="#">Home</a>
                <a class="margin1rem" href="#">About</a>
                <a class="margin1rem" href="#">Services</a>
                <a class="margin1rem" href="#">Blog</a>
                <a class="margin1rem" href="#">Contact</a>
                <a class="margin1rem" href="#">Portfolio</a>
                <button class="buttonStandard"> Sing in</button>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped  >
header{
    padding: 1rem;
}

.mainBox{
    display: flex;
    justify-content: space-between;
    align-items: center;
    *{
        margin: 0 0.5rem;
    }
}

a{
    color: white;
    text-decoration: none;
    &:hover {
        color: #F9636B ;
    }
}



</style>
