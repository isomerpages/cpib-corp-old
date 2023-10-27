---
title: Resources
permalink: /about-corruption/prevention-and-education/resources/
---


<style>
/*--------------------------------------------------------------
ALYSSA: START OF Resources PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/

/* refrain from using pure img selector as it changes the logo size */
#resources-container > section > div > a > img {
	display: block;
	border: 0;
	width: 100%;
    height: 150px;
    padding: 1em;
    border-radius: 15px 15px 0px 0px;
}

.card {
    flex: 1 0 500px;
    box-sizing: border-box;
    margin: 1rem .25em;
	background: white;
    margin-bottom: 1em;
    /* border: 0.13em solid rgba(0,0,0,.2); */
    border-radius: 15px;
    /* box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3); */
}

.card a {
  color: inherit;
  text-decoration: none; /* no underline */
}

.card-content h6 {
	padding: .5em;
	margin-top: 0.5em;
	margin-bottom: .5em;
    font-weight: bold;
    color: inherit;
    text-decoration: none;
}

.card:hover {
    transition: all 0.0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    /* top: -4px; */
    border: 2px solid #cccccc;
    background-color: white;
    margin-top: 0.5em;
	margin-bottom: .5em;
  }

.card a:hover {
  color: black;
  text-decoration: none; /* no underline */
}

/* Flexbox stuff */

.cards {
    display: flex;
    flex-wrap: wrap;
    margin: 0 auto;
    /* padding: 0 1em; */
    text-align: center;
 }

@media screen and (min-width: 40em) {
    .card {
       max-width: calc(50% -  1em);
    }
}

@media screen and (min-width: 60em) {
    .card {
        max-width: calc(33% - 1em);
    }
}

@media screen and (min-width: 52em) {
    .img {
        max-width: 52em;
    }
}

@media screen and (max-width : 480px) {
	.card { 
        max-width: 100%; }
}

/*--------------------------------------------------------------
ALYSSA: END OF Resources PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>



<main id="resources-container">
<section class="cards">
     <div class="card">
        <a href="/resources/cpib-history-book/">
                <img src="/images/cpib history book_small.jpg">
            <div class="card-content">
                <h6>Scrupulous, Thorough, Fearless - The CPIB Story</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/resources/corruzione-web-game/">
                <img src="/images/corruzione_small.png">
            <div class="card-content">
                <h6>Corruzione Web Game</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
<!--     <div class="card">   -->
<!--        <a href="/resources/virtual-heritage-gallery/">   -->
<!--                <img src="/images/resource_vhg.png">   -->
<!--            <div class="card-content">   -->
<!--                <h6>CPIB Virtual Heritage Gallery</h6>   -->
<!--            </div><!-- .card-content -->
<!--        </a>   -->
<!--    </div><!-- .card -->
    <div class="card">
        <a href="/resources/corruption-casebook">
                <img src="/images/resource_bft.jpg">
            <div class="card-content">
                <h6>Corruption Casebook – Stories from Under The Table</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/research-room/publications/anti-corruption-guide-for-businesses/">
                <img src="/images/resource_pact.jpg">
            <div class="card-content">
                <h6>About PACT</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/research-room/publications/ss-iso-37001/">
                <img src="/images/resource_ss-iso37001.jpg">
            <div class="card-content">
                <h6>About SS ISO 37001</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/resources/videos/">
                <img src="/images/resource_videos.jpg">
            <div class="card-content">
                <h6>Videos</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/resources/downloads">
                <img src="/images/resource_downloads.jpg">
            <div class="card-content">
                <h6>Downloads</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
    	<a href="/resources/info-brochures/">
           	<img src="/images/resource_info-brochures.jpg">
           <div class="card-content">
           	<h6>Informational Brochures</h6>
           </div><!-- .card-content -->
    	</a>
    </div><!-- .card -->
    <div class="card">
        <a href="https://form.gov.sg/609b7d11c32202001227a3f7" target="_blank">
                <img src="/images/resource_quiz.jpg">
            <div class="card-content">
                <h6>Quiz</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->

</section><!-- .cards -->



</main>

