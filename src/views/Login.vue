<template>
	<div class="container-scroller">
    <div class="container-fluid page-body-wrapper full-page-wrapper">
      <div class="content-wrapper d-flex align-items-center auth">
        <div class="row w-100">
          <div class="col-lg-4 mx-auto">
            <div class="auth-form-light text-left p-5">
              <div class="brand-logo">
                Buff
              </div>
              <h4>Hello! let's get started</h4>
              <h6 class="font-weight-light">Sign in to continue.</h6>
              <form class="pt-3">
                <div class="form-group">
                  <input type="email" class="form-control form-control-lg" id="exampleInputEmail1" placeholder="Username">
                </div>
                <div class="form-group">
                  <input type="password" class="form-control form-control-lg" id="exampleInputPassword1" placeholder="Password">
                </div>
                <div class="mt-3">
                  <a class="btn btn-block btn-gradient-primary btn-lg font-weight-medium auth-form-btn" href="../../index.html">SIGN IN</a>
                </div>
                <div class="my-2 d-flex justify-content-between align-items-center">
                  <div class="form-check">
                    <label class="form-check-label text-muted">
                      <input type="checkbox" class="form-check-input">
                      Keep me signed in
                    </label>
                  </div>
                  <a href="#" class="auth-link text-black">Forgot password?</a>
                </div>
                <!-- <div class="mb-2">
                  <button type="button" class="btn btn-block btn-facebook auth-form-btn">
                    <i class="mdi mdi-facebook mr-2"></i>Connect using facebook
                  </button>
                </div> -->
                <div class="text-center mt-4 font-weight-light">
                  Don't have an account? <router-link to="/register" class="text-primary">Create</router-link>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
      <!-- content-wrapper ends -->
    </div>
    <!-- page-body-wrapper ends -->
  </div>
</template>

<style scoped>
/*@import "../assets/auth/vendors/iconfonts/mdi/css/materialdesignicons.min.css";*/
/*@import "../assets/auth/vendors/css/vendor.bundle.base.css";*/
/*@import "../assets/auth/css/style.css";*/

.container-scroller {
    overflow: hidden;
}

.page-body-wrapper {
    min-height: calc(100vh - 70px);
    display: -webkit-flex;
    display: flex;
    -webkit-flex-direction: row;
    flex-direction: row;
    padding-left: 0;
    padding-right: 0;
    padding-top: 70px;
}

.page-body-wrapper.full-page-wrapper {
    width: 100%;
    min-height: 100vh;
    padding-top: 0;
}

.content-wrapper {
    background: #f2edf3;
    padding: 2.75rem 2.25rem;
    width: 100%;
    -webkit-flex-grow: 1;
    flex-grow: 1;
}

.auth .auth-form-light {
    background: #ffffff;
}

.auth .auth-form-light select {
    color: #c9c8c8;
}

.auth .auth-form-light .input-group .form-control:focus,
.auth .auth-form-light .input-group .form-control:active {
    border-color: #ebedf2;
}

.auth .brand-logo {
    margin-bottom: 2rem;
}

.auth .brand-logo img {
    width: 150px;
}

.auth form .form-group {
    margin-bottom: 1.5rem;
}

.auth form .form-group label {
    font-size: .8125rem;
}

.auth form .form-group .form-control {
    background: transparent;
    border-radius: 0;
    font-size: .9375rem;
}

.auth form .auth-form-btn {
    height: 50px;
    line-height: 1.5;
}

.auth form .auth-link {
    font-size: 0.875rem;
}

.auth form .auth-link:hover {
    color: initial;
}

.font-weight-light {
    font-family: "ubuntu-light", sans-serif;
}

.pt-3,
.py-3 {
    padding-top: 1rem !important;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-control {
    display: block;
    width: 100%;
    padding: 0.875rem 1.375rem;
    font-size: 1rem;
    line-height: 1;
    color: #495057;
    background-color: #ffffff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    border-radius: 2px;
    transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

@media screen and (prefers-reduced-motion: reduce) {
    .form-control {
        transition: none;
    }
}

.form-control::-ms-expand {
    background-color: transparent;
    border: 0;
}

.form-control:focus {
    color: #495057;
    background-color: #fff;
    border-color: #80bdff;
    outline: 0;
    box-shadow: 0 0 0 0.2rem rgba(0, 123, 255, 0.25);
}

.form-control::placeholder {
    color: #c9c8c8;
    opacity: 1;
}

.form-control:disabled,
.form-control[readonly] {
    background-color: #e9ecef;
    opacity: 1;
}

.form-control-lg {
    padding: 0.94rem 1.94rem;
    font-size: 1.25rem;
    line-height: 1.5;
    border-radius: 0.3rem;
}

.mb-4,
.my-4 {
    margin-bottom: 1.5rem !important;
}

.form-check {
    position: relative;
    display: block;
    margin-top: 15px;
    margin-bottom: 10px;
    padding-left: 0;
}

.form-check .form-check-label {
    display: block;
    margin-left: 1.75rem;
    font-size: 0.875rem;
    line-height: 1.5;
}

.rtl .form-check .form-check-label {
    margin-left: 0;
    margin-right: 1.75rem;
}

.form-check .form-check-label input {
    position: absolute;
    top: 0;
    left: 0;
    margin-left: 0;
    margin-top: 0;
    z-index: 1;
    cursor: pointer;
    opacity: 0;
    filter: alpha(opacity=0);
}

.btn-gradient-primary {
    background: linear-gradient(to right, #da8cff, #9a55ff);
    border: 0;
    -webkit-transition: opacity 0.3s ease;
    -moz-transition: opacity 0.3s ease;
    -ms-transition: opacity 0.3s ease;
    -o-transition: opacity 0.3s ease;
    transition: opacity 0.3s ease;
}

.btn-gradient-primary:not([disabled]):not(.disabled):active,
.btn-gradient-primary:not([disabled]):not(.disabled).active,
.show>.btn-gradient-primary.dropdown-toggle {
    background: linear-gradient(to right, #da8cff, #9a55ff);
}

.btn-gradient-primary:hover {
    opacity: .8;
}

.btn-gradient-primary:not(.btn-gradient-light) {
    color: #ffffff;
}

.btn-gradient-primary:not(.btn-gradient-light):hover,
.btn-gradient-primary:not(.btn-gradient-light):focus,
.btn-gradient-primary:not(.btn-gradient-light):active {
    color: #ffffff;
}


.btn {
    display: inline-block;
    font-weight: 400;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    user-select: none;
    border: 1px solid transparent;
    padding: 0.875rem 2.5rem;
    font-size: 1rem;
    line-height: 1;
    border-radius: 0.1875rem;
    transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

h4 {
	font-size: 1.13rem;
	margin-bottom: 0.5rem;
	font-weight: 500;
}

.text-primary {
    color: #b66dff !important;
}

.row {
    margin-left: 0  !important;
}
/*.mx-auto {
  margin:0 auto !important;
}*/
</style>