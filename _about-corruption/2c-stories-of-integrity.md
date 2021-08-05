---
title: Stories Of Integrity
permalink: /about-corruption/case-studies/stories-of-integrity/
third_nav_title: Case Studies
---

<style>
/*--------------------------------------------------------------
ALYSSA: START OF Stories of Integrity PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/

/* refrain from using pure img selector as it changes the logo size */
#stories-container > section > div > a > img {
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
ALYSSA: END OF Stories of Integrity PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>



<main id="stories-container">
<section class="cards">
    <div class="card">
        <a href="/cases/story_no-escape-long-arm-law">
                <img src="/images/case/story_no-escape-fr-law.jpg">
            <div class="card-content">
                <h6>No Escape From Long Arm Of Law</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_unlawful-entry-denied">
                <img src="/images/case/story_unlawful-entry.jpg">
            <div class="card-content">
                <h6>Unlawful Entry Denied</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_zero-tolerance-bribery">
                <img src="/images/case/story_zero-tolerance-to-bribery.jpg">
            <div class="card-content">
                <h6>Zero Tolerance To Bribery</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_illegal-access-denied">
                <img src="/images/case/case_pte_bagged-for-corrupt.jpg">
            <div class="card-content">
                <h6>Illegal Access Denied</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_resisting-temptation">
                <img src="/images/case/story_resisting-temptation.jpg">
            <div class="card-content">
                <h6>Resisting The Temptation</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_three-metres-too-long">
                <img src="/images/case/story_reject-bribe.jpg">
            <div class="card-content">
                <h6>Three Metres, Too Long</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_strictly-no-access">
                <img src="/images/case/case_pub_money-xchg-passes.jpg">
            <div class="card-content">
                <h6>Strictly No Access</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->
    <div class="card">
    	<a href="/cases/story_firm-enforcem-port-regulations">
           	<img src="/images/case/story_firm-enforcement-port regulations.jpg">
           <div class="card-content">
           	<h6>Firm Enforcement Of Port Regulations</h6>
           </div><!-- .card-content -->
    	</a>
    </div><!-- .card -->
    <div class="card">
        <a href="/cases/story_beyond-call-duty">
                <img src="/images/case/story_reject-bribe-drink-driving.jpg">
            <div class="card-content">
                <h6>Beyond The Call Of Duty</h6>
            </div><!-- .card-content -->
        </a>
    </div><!-- .card -->

</section><!-- .cards -->


</main>
