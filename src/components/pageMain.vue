<script >


</script>

<template>
    <main>
        <section class="ourServiceSection mainBox">
            <div>
                <p class="colorRed">Our Service</p>
                <h2>What <span>We Do</span></h2>
                <p>When, while the lovely valley teems with vapour around meand the</p>
            </div>

            <div class="cardBox">
                <div class="card">
                    <img src="../assets/images/Group-247.png" alt="">
                    <h3>Data Analysis</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-538.png" alt="">
                    <h3>SEO optimization</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-566.png" alt="">
                    <h3>Secyruty Data</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-567.png" alt="">
                    <h3>Branding Strategy</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
            </div>
            <div><button class="buttonInverted"> View All Services</button></div>
        </section>
    </main>
</template>

<style lag="scss" scoped  >
.ourServiceSection{
    padding: 75px;
    text-align: center;
}
h2{
    font-size: 38px;
    font-weight: bolder;
    margin: 1rem 0;
}
span{
    font-weight: normal;
}
.colorRed{
    color: #F9646C;
}
.cardBox{
    display: flex;
    justify-content: space-between;
    margin-top: 120px;
}
.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    width: 18%;
}
h3{
    font-size: 1.5em;
    margin: 1.5em 0;
}
button{
    margin-top: 250px;
    padding: 1em 2em;
    align-self: flex-end;
}
</style>
