<template>
  <div class="hero_area">
    <nav class="navbar navbar-expand-lg bg-white navbar-light sticky-top p-0 ">

      <div class="container-fluid d-flex justify-content-between align-items-center  ">
        <!-- โลโก้ -->
        <a href="index.html" class="navbar-brand d-flex align-items-center px-4 px-lg-5">
          <h2 class="logotext m-0 text-primary">INSPECT IQ</h2>
        </a>

        <!-- เมนูหลัก -->
        <div class="collapse navbar-collapse ms-3" id="navbarCollapse">
          <div class="navbar-nav">
            <a href="#" class="nav-item nav-link active">Home</a>
            <a href="#" class="nav-item nav-link">About</a>
            <a href="#" class="nav-item nav-link">PROFILE</a>
          </div>
        </div>

        <!-- ปุ่ม LOGOUT -->
        <div class="logout-btn ms-auto">
          <a href="" class="btn btn-primary py-4 px-lg-5 d-none d-lg-block">LOGOUT <i class="fa fa-arrow-right ms-3"></i></a>
        </div>

        <!-- ปุ่ม Toggle Navbar (สำหรับมือถือ) -->
        <button class="navbar-toggler me-4" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>

    </nav>
  </div>
</template>

<script setup>
// Your script logic here
</script>

<style scoped>
/* นำเข้า CSS */

@import '@/assets/css/style.css'; /* ใช้ path ที่ถูกต้อง */
</style>