<script>

	export let title="Nós oferecemos soluções modernas para o crescimento do seu negócio.";
	export let subTitle="Somos o time Mixou";
	export let showButton = true;
</script>

<section id="hero" class="hero d-flex align-items-center">

	<div class="container">
		<div class="row">
			<div class="col-lg-6 d-flex flex-column justify-content-center">
				<h1 data-aos="fade-up">{title}</h1>
				<h2 data-aos="fade-up" data-aos-delay="400">{subTitle}</h2>
				{#if showButton == true}
				<div data-aos="fade-up" data-aos-delay="600">
					<div class="text-center text-lg-start">
						<a href="#services" class="btn-get-started scrollto d-inline-flex align-items-center justify-content-center align-self-center">
							<span>Começar</span>
							<i class="bi bi-arrow-right"></i>
						</a>
					</div>
				</div>
				{/if}
			</div>
			<div class="col-lg-6 hero-img" data-aos="zoom-out" data-aos-delay="200">
				<img src="img/hero-img.png" class="img-fluid" alt="">
			</div>
		</div>
	</div>

</section>