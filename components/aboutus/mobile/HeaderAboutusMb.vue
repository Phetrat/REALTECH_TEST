<template>
  <div>
    <div class="headermb">
        <div class="row m-auto bg-hmb">
            <div class="col-6 text-left mt-1">
                <img src="~assets/images/image 1.svg" class="w-25" alt="">
                <img src="~assets/images/REALTECH.png" class="w-50" alt="">
            </div>
            <div class="col-6 text-right">
                <div class="hamburger-menu">
            <input id="menu__toggle" type="checkbox" />
            <label class="menu__btn" for="menu__toggle">
            <span></span>
            </label>

            <ul class="menu__box">
            <li><a class="menu__item" href="/">หน้าหลัก</a></li>
                    <li><a class="menu__item" href="#">เกี่ยวกับเรา</a></li>
                    <li><a class="menu__item" href="#">ผลงานของเรา</a></li>
                    <li><a class="menu__item" href="#">บริการของเรา</a></li>
                    <li><a class="menu__item" href="#">บทความ</a></li>
            <li><a class="menu__item" href="/joinaboutus">ร่วมงานกับเรา</a></li><li><a class="menu__item" href="#">ติดต่อเรา</a></li>
            </ul>
        </div>
            </div>
        </div>
    </div>
    <div class="h-img">
        <img src="~assets/images/Mask group.jpg" class="w-100" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.bg-hmb{
    background: linear-gradient(45deg, #f7f5f5, #d2ffe7);
}
</style>