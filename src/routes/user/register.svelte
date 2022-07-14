<script>
    import Title from '$lib/title.svelte';
</script>

<Title title="Register | Jobup" />

<!-- Header Area -->
<div class="position-absolute w-100">
    <div class="container-fluid px-0">
      <div class="row no-gutters">
        <div class="col-xl-5 col-lg-6">
          <div class="brand-logo pt-12 max-w-413 mx-auto text-center text-lg-left">
            <a href="/">
              <img class="mx-auto mx-0 light-version-logo default-logo" src="/image/logo-main-black.png" alt="">
              <img class="dark-version-logo mx-auto mx-0" src="/image/logo-main-white.png" alt="">
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- End Header Area -->
  <div class="min-height-100vh d-flex align-items-center bg-default-3">
    <div class="container-fluid h-100">
      <div class="row no-gutters align-items-center justify-content-center h-100">
        <div class="col-xl-5 col-lg-6 col-md-10">
          <div class="pt-26 pt-md-17 pt-lg-18 pb-md-4 pb-lg-10 max-w-413 mx-auto">
            <div class="mb-10" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">
              <h2 class="mb-1 font-size-10 letter-spacing-n83">Create account</h2>
              <p class="text-bali-gray font-size-7 mb-0">No credit card required</p>
            </div>
            <form action="https://finestdevs.com/" data-aos="fade-up" data-aos-duration="800" data-aos-once="true">
              <!-- Email -->
              <div class="form-group mb-6 position-relative">
                <input type="email" name="email" class="form-control form-control-lg bg-white rounded-4 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5" placeholder="Email Address" id="email">
              </div>
              <!-- Company Name -->
              <div class="form-group mb-6 position-relative">
                <input type="text" name="address" class="form-control form-control-lg bg-white rounded-4 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5" placeholder="Company name" id="company">
              </div>
              <!-- Password -->
              <div class="form-group position-relative mb-6">
                <input type="password" name="password" class="form-control form-control-lg bg-white rounded-4 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5" placeholder="Password" id="password">
              </div>
              <div class="form-group my-8">
                <label for="terms-check" class="check-input-control d-flex align-items-center">
                  <input class="d-none" type="checkbox" id="terms-check">
                  <span class="checkbox mr-5"></span>
                  <span class="mb-0 font-size-5 text-bali-gray">I agree to the  <a
                    href="https://finestdevs.com/terms-page.html" class="text-blue-3 ">Terms & Conditions</a></span>
                </label>
              </div>
              <div class="button">
                <a href="#" class="btn btn-blue-3 w-100 rounded-4">Sign up</a>
                <p class="font-size-5 mt-8 text-bali-gray" data-aos="fade-up" data-aos-duration="1100" data-aos-once="true">Already have an account? 
                    <a href="/user/login" class="text-blue-3 ">Sign in</a>
                </p>
              </div>
            </form>
          </div>
        </div>
        <!-- Right Image -->
        <div class="col-xl-7 col-lg-6 col-md-10 min-height-lg-100vh">
          <div class="bg-images min-height-100vh d-none d-lg-block" style="background-image: url(/image/inner-page/jpg/sign-up-right-img.jpg);"></div>
        </div>
      </div>
    </div>
  </div>