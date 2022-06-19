<template>
  <div>
    <div class="joinaboutus">
        <div class="row m-auto container">
        <div class="col-md-12 col-12">
            <form v-on:submit.prevent="send_data">
                <div class="mb-3">
                    <label for="InputName" class="form-label"><p>ชื่อ - สกุล</p></label>
                    <input type="text" class="form-control" id="name" placeholder="กรุณากรอกชื่อ - นามสกุล" name="name" v-model="name" onkeypress="return event.charCode >= 3585 && event.charCode <= 3641 || event.charCode >= 3648 && event.charCode <= 3660 || event.charCode = 8" aria-describedby="emailHelp">
   
                </div>
                <div class="mb-3">
                    <label for="InputPhone" class="form-label"><p>เบอร์โทรศัพท์</p></label>
                    <input type="text" class="form-control" id="phone" placeholder="กรุณากรอกเบอร์โทรศัพท์" name="phone" v-model="phone" onkeypress="return event.charCode >= 48 && event.charCode <= 57"  maxlength="10">
                </div>
                <button type="submit" class="btn btn-success"><p class="text-white">Submit</p></button>
            </form>
            <div class="show-data">
                <p>{{ this.show_name }}</p>
                <p>{{ this.show_phone }}</p>
            </div>
        </div>
    </div>
    </div>
    <footer-pc/>
  </div>
</template>

<script>
import FooterPc from './pc/FooterPc.vue';
export default {
  components: { FooterPc },
 data() {
    return {
          name: "",
          phone: "",
          show_name: "",
          show_phone: ""
    };
  },
  methods: {
      send_data() {
          if (this.name == '' || this.name == null || this.phone == '' || this.phone == null || this.phone.length < 10) {
                this.$swal({
                    icon: 'error',
                    text: 'กรุณากรอกข้อมูลให้ถูกต้อง',
                    confirmButtonColor: '#28a745',
                });
            } else if(this.phone.length == 10) {     
                this.show_name = 'ชื่อ - นามสกุล : ' + this.name
                this.show_phone = 'เบอร์โทรศัพท์ : ' + this.phone
            }else{
                this.$swal({
                    icon: 'error',
                    text: 'กรุณากรอกข้อมูลให้ถูกต้อง',
                    confirmButtonColor: '#28a745',
                })
            }
        // alert('ss')
      }
  },
}
</script>

<style>
.joinaboutus{
    background: linear-gradient(360deg, #f7f5f5, #d2ffe7);
    padding: 3rem;
}
.show-data{
    margin-top: 2rem;
}
</style>