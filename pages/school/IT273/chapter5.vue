<template>
	<div class="c5">
		<div class="title">Chapter 5</div>

		<div class="lists">
			<div class="unlist">
				<h2>Names  <span>Unordered List</span></h2>
				<br>
				<ul class="list-disc">
					<li>Thea</li>
					<li>Kalel</li>
					<li>Kristel</li>
					<li>Christian</li>
				</ul>
			</div>
			<br>
			<div class="unlist">
				<h2>Steps on how to learn to code  <span>Ordered List</span></h2>
				<br>
				<ol class="list-decimal">
					<li>Open your computer</li>
					<li>Surf the internet and choose what you wannt to learn.</li>
					<li>Read the documentation or watch other people on how they're doing it</li>
					<li>Practice</li>
					<li>Repeat</li>
				</ol>
			</div>
			<br>
			<div class="unlist">
				<h2>Languages and Frameworks  <span>Discription List</span></h2>
				<br>
				<dl>
					<dt>Javascript</dt>
  					<dd>Nodejs</dd>
  					<dd>Vuejs</dd>
  					<dd>Angular</dd>
  					<br>
  					<dt>Php</dt>
  					<dd>Laravel</dd>
  					<dd>Codeigniter</dd>
  					<br>
  					<dt>Javascript</dt>
  					<dd>Nodejs</dd>
				</dl>
			</div>
		</div>


		<NuxtLink to="/school/it273">
			<button class="back"><svg class="w-6 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"></path></svg></button>
		</NuxtLink>
	</div>
</template>

<style scoped>
	.c5 {
	  padding: 40px 20px;
	  font-size: 13px;
   }

   .title {
   	display: grid;
   	place-items: center;
   	font-size: 18px;
   }

   .lists {
   	 margin: 20px 0;
   }

   .unlist {
   	width: fit-content;
   	background-color: var(--menubg);
   	padding: 20px;
   	border-radius: 8px;
    box-shadow: 0 10px 40px -10px rgb(0 64 128 / 20%);
    transition: box-shadow .3s;
   }

   ul, ol {
   	padding-left: 20px;
   }

   dt {
   	position: relative;
   }

   dd {
   	margin-left: 15px;
   }

   span {
   	margin-left: 4px;
   	font-size: 10px;
   	padding: 4px 10px;
   	border-radius: 4px;
   	color: var(--hero1color);
   	background-color: var(--hero1bg);
   }

   .back {
    outline: 0;
   position: absolute;
   top: 0;
     cursor: pointer; 
     background-color: var(--hero1bg);
     color: var(--hero1color);
     padding: 4px 8px; 
     border-radius: 50%;
     font-size: 13px;
     margin-top: 20px;
   }
</style>