<script>
import Corousel from "$components/home/Corousel/Corousel.svelte";
</script>

<div class="">
	<h1 class="HEADER mx-auto pt-2 text-center text-3xl font-semibold text-aisha">
		AISHA BIRTHDAY WISHES
	</h1>
	<h1 class="HEADER mx-auto -mt-1 pb-2 text-center text-2xl">ร่วมเขียนคำอวยพรให้ไอช่ากัน!</h1>
	<div class="font-[itim]">
		<Corousel /> </div>
	<hr class="my-4 h-1 bg-aisha" />

</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Noto+Sans+Thai+Looped:wght@100;200;300;400;500;600;700;800;900&display=swap');
	@font-face {
		font-family: 'Barlow Condensed';
		src: url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Noto+Sans+Thai+Looped:wght@100;200;300;400;500;600;700;800;900&display=swap')
			format('truetype');
	}
	@font-face {
		font-family: 'Noto Sans Thai Looped';
		src: url('https://fonts.googleapis.com/css2?family=Barlow+Condensed:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Noto+Sans+Thai+Looped:wght@100;200;300;400;500;600;700;800;900&display=swap')
			format('truetype');
		unicode-range: U+0E00, U+0E7F; /* Latin glyphs */
	}
	.HEADER {
		font-family: 'Barlow Condensed', 'Noto Sans Thai Looped', sans-serif;
	}
</style>
