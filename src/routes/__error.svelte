<script context="module">
	/** @type {import('@sveltejs/kit').Load} */
	export function load({ error, status }) {
		return {
			props: { error, status }
		};
	}
</script>

<script>
	/** @type {number} */
	export let status;

	/** @type {Error & {frame?: string} & {loc?: object}} */
	export let error;
</script>

<div class="pt-24 pt-md-26 pb-15 pt-lg-33 pb-md-19 pb-lg-25">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-xl-5 col-lg-6 col-md-8 col-sm-11">
          <div class="text-center">
            <div class="mb-8 mb-lg-16" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">
              <img class="w-100 w-xs-auto" src="image/inner-page/png/404-error-img.png" alt="">
            </div>
            <h1 class="font-size-13 mb-8" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">404 Error</h1>
            <p class="font-size-7 mb-0" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">The page you are looking for is not available or doesn’t belong to this website!</p>
            <div class="">
              <div class="pt-11 max-w-322 mx-auto" data-aos="fade-up" data-aos-duration="500" data-aos-once="true">
                <a class="btn btn-bali-gray w-100 rounded-5 text-white" href="#">Go back to home</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>


<!-- TODO figure out what to do with frames/stacktraces in prod -->
<!-- frame is populated by Svelte in its CompileError and is a Rollup/Vite convention -->
<!-- {#if error.frame}
	<pre>{error.frame}</pre>
{/if}
{#if error.stack}
	<pre>{error.stack}</pre>
{/if} -->



