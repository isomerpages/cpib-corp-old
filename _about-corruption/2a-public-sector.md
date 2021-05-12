---
title: Public Sector
permalink: /about-corruption/case-studies/public-sector/
third_nav_title: Case Studies
---


<style>
/*--------------------------------------------------------------
ALYSSA: START OF PUBLIC SECTOR CASE STUDIES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
/* refrain from using pure img selector as it changes the logo size */

#public-case-container > div > div > a > img {
    display: block;
    border: 0;
    max-width: 180px;
    max-height: auto;
    padding: 1em;
    border-radius: 15px 15px 0px 0px;
}

.card {
    flex: 1 0 500px;
    box-sizing: border-box;
    margin: 1em 0.5em;
    background: white;
    margin-bottom: 1em;
    border: 0.13em solid rgba(0,0,0,.1);
    border-radius: 15px;
    /* box-shadow: 2px 2px 6px 0px  rgba(0,0,0,0.3); */
}

.card a {
    color: inherit;
    text-decoration: none; /* no underline */
}

.card p,
.card-content h5 {
    padding: 1em;
    margin-top: 0.5em;
    margin-bottom: .5em;
    /* font-weight: bold; */
    color: inherit;
    text-decoration: none;
}

.card:hover {
    transition: all 0s ease-out;
    box-shadow: 0px 4px 8px rgba(38, 38, 38, 0.2);
    top: -4px;
    border: 2px solid #cccccc;
    background-color: white;
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
ALYSSA: END OF PUBLIC SECTOR CASE STUDIES PAGE CARDS FLEXBOX LAYOUT AND STYLES
--------------------------------------------------------------*/
</style>


<div id="public-case-container">
<div class="cards">
    <div class="card">
        <a href="/files/case_pub_fugitive-brought-justice-after-35-years.pdf" target="_blank">  
            <div class="card-content">
            <h5>Fugitive Brought to Justice After 35 Years</h5>
            </div>
          <img src="/images/case/case_pub_brought-to-justice.jpg" style="width:300px;">
        </a>
    </div>
</div>
<!-- container end dic -->
</div>
