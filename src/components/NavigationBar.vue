<template>
	<div class="navigation">
		<input id='navi-toggle' type="checkbox" class="navigation__check-box">
		<label for="navi-toggle" class="navigation__button"><span class='navigation__icon'></span></label>

		<div class="navigation__background"></div>

		<nav class="navigation__nav">
			<ul class="navigation__list">
				<li class="navigation__item"><a href="#section-about" class="navigation__link" @click='unchecked'><span>01</span> About Natours</a></li>
				<li class="navigation__item"><a href="#section-benifits" class="navigation__link" @click='unchecked'><span>02</span> Your Benifits</a></li>
				<li class="navigation__item"><a href="#head-tours-div" class="navigation__link" @click='unchecked'><span>03</span> Popular tours</a></li>
				<li class="navigation__item"><a href="#section-stories" class="navigation__link" @click='unchecked'><span>04</span> Stories</a></li>
				<li class="navigation__item"><a href="#section-book" class="navigation__link" @click='unchecked'><span>05</span> Book Now</a></li>
			</ul>
		</nav>
	</div>
</template>

<script>
	
	export default {
		data() {
			return {
			}
		},
		methods: {
			unchecked() {
				document.querySelector('input').checked = false;
			}
		}
	}
</script>