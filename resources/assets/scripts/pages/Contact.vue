<template>
	<div>
		<div class="row">
			<div class="col-lg-6 col-primary">
				<contact-form></contact-form>
				<map-canvas position="56.484392,21.017387" zoom="4" icon="/images/mapmarker.png"></map-canvas>
			</div>
			<div class="col-lg-6 flex-first flex-lg-unordered">
				<h1 class="title title--spaced">Contact me</h1>
				
				<div class="list-group">
					<div class="list-group-item">
						<p class="item-title">Email</p>
						<p><a href="rexsteroxy22@gmail.com">rexsteroxy22@gmail.com</a></p>
					</div>
					<div class="list-group-item">
						<p class="item-title">Phone</p>
						<p><a href="tel:+2349037096290">+2349037096290</a></p>
					</div>
					<div class="list-group-item">
						<p class="item-title">Address</p>
						<p>Bishops court Owerri Imo State</p>
					</div>
				</div>
			</div>
		</div>
		
	</div>
</template>
<script>
import MapCanvas from '../components/MapCanvas.vue';
import ContactForm from '../components/ContactForm.vue';
import Typed from 'typed.js'
export default {
	components : {
		MapCanvas,
		ContactForm
	}
}
</script>
