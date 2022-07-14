<script>
    import Title from '$lib/title.svelte';
</script>

<Title title="Login | Jobup" />

<div class="position-absolute w-100">
    <div class="container-fluid px-0">
      <div class="row no-gutters">
        <div class="col-xl-5 col-lg-6">
          <div class="brand-logo pt-12 max-w-413 mx-auto  text-center text-lg-left">
            <a href="javascript:">
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
    <div class="container-fluid h-100 px-0">
      <div class="row no-gutters align-items-center justify-content-center h-100">
        <div class="col-xl-5 col-lg-6 col-md-10">
          <div class="pt-26 pt-md-17 pt-lg-18 pb-md-4 pb-lg-10 max-w-413 mx-auto" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">
            <div class="mb-10 text-center text-lg-left">
              <h2 class="mb-1 font-size-10 letter-spacing-n83">Welcome back</h2>
              <p class="text-bali-gray font-size-7 mb-0">Enter your account details below</p>
            </div>
            <form action="https://finestdevs.com/" data-aos="fade-up" data-aos-duration="800" data-aos-once="true">
              <!-- Email -->
              <div class="form-group mb-6 position-relative">
                <input type="email" name="email" class="form-control form-control-lg bg-white rounded-4 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5" placeholder="Email Address" id="email">
              </div>
              <!-- Password -->
              <div class="form-group position-relative mb-6">
                <input type="password" name="password" class="form-control form-control-lg bg-white rounded-4 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5" placeholder="Password" id="password">
                <a href="/user/reset-password" class="btn-link text-light-orange absolute-center-right mr-6">Forgot
                  Password?</a>
              </div>
              <!-- Checkbox -->
              <div class="form-group mb-6 d-flex align-content-center">
                <label for="terms-check" class="check-input-control d-flex align-items-center mb-0">
                  <input class="d-none" type="checkbox" id="terms-check">
                  <span class="checkbox mr-5"></span>
                </label>
                <p class="mb-0 font-size-5 text-bali-gray">Keep me signed in</p>
              </div>
              <!-- Button -->
              <div class="button">
                <a href="/user/register" class="btn btn-blue-3  w-100 rounded-4">Sign in</a>
                <p class="font-size-5 mt-8 text-bali-gray" data-aos="fade-up" data-aos-duration="1100" data-aos-once="true">Don’t have an account? 
                  <a href="/user/register" class="text-blue-3 ">Create a free
                    account</a>
                </p>
              </div>
            </form>
          </div>
        </div>
        <!-- Right Image -->
        <div class="col-xl-7 col-lg-6 col-md-10 min-height-lg-100vh">
          <div class="bg-images min-height-100vh d-none d-lg-block" style="background-image: url(/image/inner-page/jpg/sign-in-right-img.jpg);"></div>
        </div>
      </div>
    </div>
  </div>