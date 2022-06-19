<template>
  <div class="row m-auto text-center">
    <div class="col-md-6 col-12 ">
        <img src="~assets/images/CONTINUE.png" class="w-100 d-none d-md-block" alt="">
         <img src="~assets/images/CONTINUE.png" class="w-100 px-5 mt-3 d-block d-md-none" alt="">
    </div>
    <div class="col-md-12 col-6">
        <div class="blog mt-5">
            <h3 class="d-head">BLOG</h3>
            <slide-blog/>
        </div>
    </div>
    <div class="col-md-6 col-12">
        <img src="~assets/images/web-realtech-poster 1.png" class="w-100" alt="">
    </div>
    <div class="col-md-6 col-12">
        <img src="~assets/images/title-ourvision.png" class="i-title mt-3" alt="">
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/Vector (3).png" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>DREAM</span></h3>
                <p class="txt-p">ฝันที่ยิ่งใหญ่</p>
            </div>
        </div>
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/Vector (4).png" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>BEGIN</span></h3>
                <p class="txt-p">จุดเริ่มต้นความสร้างสรรค์</p>
            </div>
        </div>
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/Vector (5).png" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>HOME</span></h3>
                <p class="txt-p">ไม่สิ้นหวัง</p>
            </div>
        </div>
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/Fingerprint_scan.svg" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>US</span></h3>
                <p class="txt-p">เป็นตัวของตัวเอง</p>
            </div>
        </div>
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/Group 32.png" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>LIGHT</span></h3>
                <p class="txt-p">เส้นทางสู่ความสำเร็จ</p>
            </div>
        </div>
        <div class="row m-auto">
            <div class="col-md-3 col-3" >
                <img src="~assets/images/image 1.svg" class="w-50 mt-3" alt="">
            </div>
            <div class="col-md-9 col-9 text-left">
                <h3>REAL &nbsp;<span>TECH</span></h3>
                <p class="txt-p">REAL &nbsp;YOU</p>
            </div>
        </div>

    </div>
  </div>
</template>

<script>
import SlideBlog from './SlideBlog.vue'
export default {
  components: { SlideBlog },

}
</script>

<style>
.blog{
    text-align: center;
}
.slide-blog{
    line-height: 100px;
    margin: 10px;
    padding: 2%;
    position: relative;
    text-align: center;
}
h3 span{
    color: #145343;
}
.i-title{
    width: 70%;
}
.txt-p{
    color: #2aa571;
}
</style>