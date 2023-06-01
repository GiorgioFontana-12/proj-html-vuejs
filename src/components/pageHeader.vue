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
                <button> Sing in</button>
            </div>
        </div>
    </header>
</template>

<style lag="scss" scoped  >
header{
    background-color: #0B1852 ;
    padding: 1rem;
}

.mainBox{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

a{
    color: white;
    margin: 0.5rem;
    text-decoration: none;
    &:hover {
        color: #F9636B ;
    }
}
button{
    padding: 0.5rem 0.8rem;
    border: none;
    border-radius: 1rem;
    color: white;
    margin-left: 0.5rem;
    background: rgb(4,164,208);
    background: -moz-linear-gradient(90deg, rgba(4,164,208,1) 30%, rgba(31,63,131,1) 80%);
    background: -webkit-linear-gradient(90deg, rgba(4,164,208,1) 30%, rgba(31,63,131,1) 80%);
    background: linear-gradient(90deg, rgba(4,164,208,1) 30%, rgba(31,63,131,1) 80%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#04a4d0",endColorstr="#1f3f83",GradientType=1);
    &:hover{
        cursor: pointer;
        background: rgb(184,38,110);
        background: -moz-linear-gradient(90deg, rgba(184,38,110,1) 30%, rgba(248,98,107,1) 80%);
        background: -webkit-linear-gradient(90deg, rgba(184,38,110,1) 30%, rgba(248,98,107,1) 80%);
        background: linear-gradient(90deg, rgba(184,38,110,1) 30%, rgba(248,98,107,1) 80%);
        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#b8266e",endColorstr="#f8626b",GradientType=1);
    }
    }



</style>
