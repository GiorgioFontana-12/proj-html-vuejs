<script >
    import { Navigation, Pagination, Scrollbar, A11y } from 'swiper';
    import { Swiper, SwiperSlide } from 'swiper/vue';
    import 'swiper/css';
    import 'swiper/css/navigation';
    import 'swiper/css/pagination';
    import 'swiper/css/scrollbar';
    export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      const onSwiper = (swiper) => {
        console.log(swiper);
      };
      const onSlideChange = () => {
        console.log('slide change');
      };
      return {
        onSwiper,
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y],
      };
    },
  };

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
                    <img src="../assets/images/Group-247.png" alt="Group-247">
                    <h3>Data Analysis</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-538.png" alt="Group-538">
                    <h3>SEO optimization</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-566.png" alt="Group-566">
                    <h3>Secyruty Data</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
                <div class="card">
                    <img src="../assets/images/Group-567.png" alt="Group-567">
                    <h3>Branding Strategy</h3>
                    <p>When, While the lovely velley teems with vapour around meand the meridian sun strikes the upper</p>
                </div>
            </div>
            <div><button class="buttonInverted"> View All Services</button></div>
        </section>


            <section class="StartYourProject  gradientBackground ">
                <div class="mainBox flex">
                    
                    <div class="width60">
                        <img src="../assets/images/men-data.png" alt="men-data">
                    </div>

                    <div class="width40 marginLeft3rem">
                        <div >
                            <p>Start Your Project</p>
                            <h1><strong>Growt Your Business</strong> </h1>
                            <h1>With Our Strategy</h1>
                        </div>
                        <div>
                            <p class="textBlu">When, while the lovely valley teems with vapour around meand the meridian sun strikes the upper surface. Of the impenetrable follage of my trees, and but a few stray gleams steal into the inner sanctuary.</p>
                        </div>

                        <div>
                            <button class="buttonInverted">Try it Now</button>
                            <button class="buttonStandard">Explore More </button>
                        </div>
                    </div>

                </div>
            </section>

            <section class="portfolio">
                <div  >
                    <div class="mainBox">
                        <p class="colorRed">Portfolio</p>
                        <h2>Latest <span>Work</span> </h2>
                    </div>
                    <div>
                        <swiper class="center" :modules="modules" :slides-per-view="3" :space-between="0" navigation :pagination="{ clickable: true }"  @swiper="onSwiper" @slideChange="onSlideChange">
                            <swiper-slide class="marginLeft">
                                <div class="card">
                                    <img src="../assets/images/8wa60okr-1-790x576.jpg" alt="">
                                    <div>
                                        <h4>Basket of Dlower on table</h4>
                                        <p>Branding Strategy</p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="../assets/images/DRY-1-790x576.jpg" alt="">
                                    <div>
                                        <h4>Purinky Products</h4>
                                        <p>Digital Experience</p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="../assets/images/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg" alt="">
                                    <div>
                                        <h4>Satisfy Poster</h4>
                                        <p>Branding Strategy</p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="../assets/images/84316050-0af0-49db-a53a-241d47ddad0e-2-790x576.jpg" alt="">
                                    <div>
                                        <h4></h4>
                                        <p></p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="" alt="">
                                    <div>
                                        <h4></h4>
                                        <p></p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="" alt="">
                                    <div>
                                        <h4></h4>
                                        <p></p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="" alt="">
                                    <div>
                                        <h4></h4>
                                        <p></p>
                                    </div>
                                </div>

                            </swiper-slide>
                            <swiper-slide>
                                <div class="card">
                                    <img src="" alt="">
                                    <div>
                                        <h4></h4>
                                        <p></p>
                                    </div>
                                </div>

                            </swiper-slide>
                            
                         </swiper>
                    </div>

                </div>

            </section>
    </main>
</template>

<style lang="scss" scoped  >
.ourServiceSection{
    padding: 75px 0;
    text-align: center;
    .buttonInverted{
         margin-top: 250px;
         padding: 1em 2em;
    }
}
h2{
    font-size: 38px;
    font-weight: bolder;
    margin: 1rem 0;
}
span{
    font-weight: normal;
}

.cardBox{
    display: flex;
    justify-content: space-around;
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

.flex{
    display: flex;
}

.StartYourProject {
    padding: 100px 0;
    
    .width60{
        padding: 0 120px;
        img{
            width: 100%;
        }
    }
    .width40{
        display: flex;
        flex-direction: column;
        justify-content: center;
        p{
            color: white;
        }
        h2{
            color: white;
        }
        .textBlu{
            margin: 1rem 0;
        }
        
        .buttonInverted,.buttonStandard {
            width: 180px !important;
            height: 50px !important;
            text-align: center;
            margin-right: 1rem;
            margin-top: 2rem;
        }
        h1{
        color: white;
        font-size: 3rem;
        font-weight: normal;
        margin: 0.2em 0; 
        }
        strong{
            font-weight: bolder;
    }
    }
    .marginLeft3rem{
        margin-left: 3rem;
    }
    }

.portfolio{
    padding: 80px 0;
    .marginLeft{
        margin-left: 50px;

    }
    .center{
        padding: 80px 200px ;
    }
    .card{
        width: 400px;
        height: 310px;
        border-radius: 15px;
        box-shadow: 1px 1px 120px -50px rgba(0,0,0,0.69);
        -webkit-box-shadow: 1px 1px 120px -50px rgba(0,0,0,0.69);
        -moz-box-shadow: 1px 1px 120px -50px rgba(0,0,0,0.69);
        img{
            display: block;
            width: 100%;
            height: 250px;
            border-radius: 15px;
            margin-bottom: 0.8rem;
        }
    }
}


</style>
