<template>
  <div class="footer">
    <div class="f-tab mt-5">
        <h1 class="text-white">REAL<b>TECH</b>&nbsp;&nbsp; <span>เพื่อนร่วมทางสู่ความสำเร็จ</span></h1>
    </div>
    <div class="bg-footer">
        <div class="container row m-auto">
            <div class="col">
                <img src="~assets/images/logo-realtech-f.png" class="w-100 d-none d-md-block" alt="">
                <img src="~assets/images/logo-realtech-f.png" class="w-50 d-md-none d-block" alt="">
            </div>
            <div class="col mt-5 mb-5 d-md-block d-none">
                <h2>ABOUT REALTECH</h2>
                <a href="/"><p>หน้าหลัก</p></a>
                <a href="#"><p>เกี่ยวกับเรา</p></a>
                <a href="#"><p>ผลงานของเรา</p></a>
                <a href="/joinaboutus"><p>ร่วมงานกับเรา</p></a>
            </div>
            <div class="col mt-5 d-md-block d-none">
                <h2>OUR SERVICES</h2>
                <a href="#"><p>Solution Platform</p></a>
                <a href="#"><p>Business Digital Transformation</p></a>
                <a href="#"><p>Digital Marketing Service</p></a>
            </div>
            <div class="col mt-5 d-md-block d-none">
                <h2>SUPPORT</h2>
                 <a href="#"><p>ติดต่อเรา</p></a>
            </div>
            <div class="col mt-5">
                <div class="row">
                    <div class="col-md-2 col-2"><i class="fa fa-home"></i></div>
                    <div class="col-md-10 col-10"><p> อาคาร Liberty Plaza ชั้น 10 1000 ซอยสุขุมวิท 55 ถนนสุขุมวิท แขวงคลองตันเหนือ เขตวัฒนา กรุงเพทฯ 10110</p></div>
                </div>
                <div class="row">
                    <div class="col-md-2 col-2"><i class="fab fa-line"></i></div>
                    <div class="col-md-10 col-10"><p> @realtech-th</p></div>
                </div>
                <div class="row">
                    <div class="col-md-2 col-2"><i class="fab fa-facebook"></i></div>
                    <div class="col-md-10 col-10"><p> Realtech - เรอัลเทค</p></div>
                </div>
            </div>
        </div>
    </div>
    <div class="f-copyright">
        <p class="text-white">Copyright 2021, www.realtech-th.com .All right reserved.</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.f-tab{
       background: linear-gradient( 90deg, rgb(23 97 76) 0%, rgb(50 165 78) 45%, rgb(23 97 76) 100% );
    padding: 0.5rem;
    text-align: center;
}
h1{
    font-size: 2.5rem;
    font-weight: normal;
    margin: 1rem;
}
h1 span{
    font-size: 1.5rem;
}
.bg-footer{
    background-image: url('/bg-footer.jpg');
    width: 100%;
    background-position-x: center;
    background-position-y: center;
    background-repeat: no-repeat;
}
a p{
    color: #2aa571;
}
a:hover p{
    color: #1c715c;
}
a:hover{
    
    text-decoration: none;
}
.fa, .fab{
    font-size: 1.1rem;
    color: #1a6955;
}
.f-copyright{
    background: rgb(29 123 96) 100%;
    padding: 0.3rem;
    text-align: center;
}
</style>