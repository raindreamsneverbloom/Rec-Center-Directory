<div class="Homepage">
<title>Rec Center Directory</title>



<h1 class=text-white>Rec Center Directory</h1>

<a href="/Equipment-List" class="home_button">
  View Equipment List
</a>
<p class=text-white>What floor contains each peice of equipment</p>


<!--
<a href="/General-Directory" class="home_button">
  General Building Breakdown
</a>

<a href="/About-Page" class="home_button">
  About this Website
</a>

<a href="/Floor-List" class="home_button">
  Detailed Floor Lists
</a>

-->

<div class="button-stack">
  <a href="/General-Directory" class="home_button">
  General Building Breakdown</a>
<a href="/About-Page" class="home_button">
  About this Website</a>
<a href="/Floor-List" class="home_button">
  Detailed Floor Lists</a>
</div>


</div>


<style>

    .home_button{
    display: inline-block;       /* Ensures margin works */
    margin-top: 0.5rem;            /* Adds space above */
    margin-bottom: 0.1rem;       /* Adds space below */
    padding: 0.5rem 1rem;
    background-color: #1555d4;   /* Tailwind gray-200 */
    color: rgb(255, 255, 255);
    border-radius: 0.375rem;
    text-decoration: none;
    transition: background-color 0.2s ease;
    margin-left: 0.25rem;   /* Adds space to the left */
  }

  .button-stack {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  align-items: center;
  margin-top: 2rem;
}

  .Homepage {
  background-color: rgb(43, 39, 39);
  min-height: 100vh; /* fills full vertical space */

}


</style>