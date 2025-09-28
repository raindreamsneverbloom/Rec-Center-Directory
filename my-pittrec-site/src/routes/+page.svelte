<div class="Homepage">
<title>Rec Center Directory</title>



<h1 class=heading>Rec Center Directory</h1>
<!--
<p class="label-text">What floor contains each peice of equipment:</p>
-->
<div class="button-stack">
<a href="/Equipment-List" class="home_button">
  View Equipment List
</a>
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
    background-color: rgba(255, 205, 5, 0.877);   /* Tailwind gray-200 */
    color:  rgb(10, 40, 70);
    border-radius: 0.375rem;
    text-decoration: none;
    transition: background-color 0.2s ease;
    margin-left: 0.25rem;   /* Adds space to the left */
    font-family: 'EB Garamond', serif;
    font-size:1.175rem;
    font-weight: 500;
  }

  .button-stack {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  align-items: center;
  margin-top: 2rem;
  font-family: 'EB Garamond', serif;
}
/*
  .label-text{
    color: antiquewhite;
    font-family: 'EB Garamond', serif;
    font-size:1.175rem;
    padding-left: 01rem;
    text-align: center;
    }
*/

  .heading{
    color: antiquewhite;
    font-family: 'EB Garamond', serif;
    font-size:2rem;
    padding-left: 01rem;
    font-weight: 600;
    text-align: center;
    margin-bottom: 2.5rem;
    padding-top: 1rem;
  }


  .Homepage {
  background-color: rgb(55, 58, 61);;
  min-height: 100vh; /* fills full vertical space */

}


</style>