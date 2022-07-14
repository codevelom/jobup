<script>
    import Title from "$lib/title.svelte";
    import ContactForm from "$lib/contact-form.svelte";

</script>

<Title title="Contact Us" />

<div class="min-height-100vh d-flex align-items-center pt-23 pt-md-26 pt-lg-30 pb-8 pb-md-12 pb-lg-23">
    <div class="container">
      <!-- Section Title -->
      <div class="row justify-content-center">
        <div class="col-xl-12">
          <div class="mb-10 mb-lg-18 text-center" data-aos="fade-up" data-aos-duration="300" data-aos-once="true">
            <h2 class="font-size-11 mb-7">Contact us</h2>
            <p class="font-size-7 mb-0">Send us a message and we will reply you within 48 hours.</p>
          </div>
        </div>
      </div>
      <!-- End Section Title -->
      <!-- Contact Form -->
      <div class="row justify-content-center">
        <div class="col-12">
          <!-- contact details -->
          <div class="top-contact-info bg-default-1 max-w-540 mx-auto py-10 px-13 rounded-10" data-aos="fade-up" data-aos-duration="600" data-aos-once="true">
            <div class="row">
              <div class="col-lg-6 mb-5 mb-lg-0">
                <div class="border-md-right border-cornflower-blue">
                  <h4 class="font-size-5 text-default-color font-weight-normal mb-0">Call us</h4>
                  <a class="font-size-7 font-weight-bold heading-default-color" href="#">+1-394-429-3985</a>
                </div>
              </div>
              <div class="col-lg-6 mb-5 mb-lg-0">
                <div class="pl-1 pr-3">
                  <h4 class="font-size-5 text-default-color font-weight-normal mb-0">Email us</h4>
                  <a class="font-size-7 font-weight-bold heading-default-color" href="#">support@finity.com</a>
                </div>
              </div>
            </div>
          </div>
          <!-- contact details -->
          <div class="pt-12 pb-10 max-w-536 mx-auto">
            <form action="https://finestdevs.com/" data-aos="fade-up" data-aos-duration="1100" data-aos-once="true">
              <!-- Company Name -->
              <div class="form-group mb-7 position-relative">
                <input type="text" name="name" class="form-control form-control-lg bg-white rounded-5 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5 border-default-color" placeholder="John Doe" id="company">
              </div>
              <!-- Email -->
              <div class="form-group mb-7 position-relative">
                <input type="email" name="email" class="form-control form-control-lg bg-white rounded-5 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5 border-default-color" placeholder="Email Address" id="email">
              </div>
              <!-- Company Name -->
              <div class="form-group mb-7 position-relative">
                <input type="text" name="subject" class="form-control form-control-lg bg-white rounded-5 text-dark-cloud text-placeholder-bali-gray pl-7 font-size-5 border-default-color" placeholder="Subject" id="subject">
              </div>
              <!-- Company Name -->
              <div class="form-group mb-7 position-relative">
                <textarea name="message" id="message" placeholder="Type your message" class="form-control form-control-lg bg-white rounded-5 text-dark-cloud text-placeholder-bali-gray pl-7 pt-7 font-size-5 border-default-color"></textarea>
              </div>
              <div class="button">
                <a href="#" class="btn btn-blue-3 h-55 w-100 rounded-4">Send</a>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
