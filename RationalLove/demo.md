# RATIONAL LOVE 

Mathematics Day

American Center

Dec 19, 2024





### What to expect from today
## FUN<!-- .element: class="fragment" -->



### Why do you have to study math?

<ul>
    <li class="fragment"> "Too theoretical"/not applicable </li>
    <li class="fragment"> Can't make money</li>
    <li class="fragment"> Difficult </li>
    <li class="fragment"> Boring </li>
</ul>
<h2 class="fragment"> WRONG! </h>


## Agenda
- Setup <!-- .element: class="fragment" -->
- Develop Strategy <!-- .element: class="fragment" -->
- Proof that the strategy works <!-- .element: class="fragment" -->



<section data-auto-animate>
    <h1>BUSINESS</h1>
</section>
<section data-auto-animate>
    <h1>BUSINESS</h1>
    <h2> Groups of 5 or 6</h2>
</section>



<section data-auto-animate>
    <h3>How does one choose who to date/marry?</h3>
</section>
<section data-auto-animate>
    <h3>How does one choose who to date/marry?</h3>
    <iframe width="800" height="450" src="https://www.youtube.com/embed/59Hj7bp38f8?si=gslT6_POU9omK1G7" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</section>



<section data-auto-animate>
    <h3>How does one choose who to date/marry?</h3>
</section>
<section data-auto-animate>
    <h3>How does one choose who to date/marry?</h3>
    <p">Look</p>
    <p class="fragment">Background</p>
    <p class="fragment">Education</p>
    <p class="fragment">Finance</p>
    <p class="fragment">Temperament</p>
    <p class="fragment">Vibe</p>
</section>



<section>
    <img data-src="RationalLove/dating/tinder.webp" height="20%" width="20%">
<img data-src="RationalLove/dating/bumble.png" height="20%" width="20%">
<img data-src="RationalLove/dating/hinge.png" height="20%" width="20%" style="filter: invert(100%);-webkit-filter: invert(100%);">
<img data-src="RationalLove/dating/facebook.jpeg" height="20%" width="20%">
</section>



<section>
    <img data-src="RationalLove/dating/cavalier.jpeg" height="50%" width="50%">
</section>


<section>
    <img data-src="RationalLove/dating/monalisa.jpeg" height="50%" width="50%">
</section>



<section data-auto-animate> 
    <h2>Why?</h2>
</section>
<section data-auto-animate> 
    <h2>Why?</h2>
    <h3>Find your one true love forever, of course</h3>
</section>



## MATH?



<section data-auto-animate>
    <h2>Ideas</h2>
</section>
<section data-auto-animate>
    <h2>Ideas</h2>
    <p>Ranking</p>
    <p class="fragment">Stable Equilibrium</p>
</section>



<section data-auto-animate>
    <h2>Market rules</h2>
</section>
<section data-auto-animate>
    <h2>Market rules</h2>
    <ol>
        <li>Each person can only have 1 match at a time</li>
        <li class="fragment">It is always better to have a partner than not</li>
        <li class="fragment">Man-Woman couples only</li>
        <li class="fragment">Simplest case: men = women</li>
    </ol>
</section>



<section data-auto-animate>
    <h3>Personal preference list</h3>
</section>
<section data-auto-animate>
    <h3>Personal preference list</h3>

|   | Cavalier    | Leon        |
| - | ----------- | ----------- |
| 1 | Madame Lisa | Madame Lisa |
| 2 | Pearl       | Pearl       |

---

|   | Madame Lisa | Pearl    |
| - | ----------- | -------- |
| 1 | Cavalier    | Leon     |
| 2 | Leon        | Cavalier |

</section>



<section data-auto-animate>
    <h3>Stable equilibrium</h3>
</section>
<section data-auto-animate>
    <h3>Stable equilibrium</h3>
    <p> A configuration of matches so that there is no pair of man and woman, who are
    not together BUT want to be together  MORE than with their current partners. </p>
</section>



TASK: Match them up in a way that creates a stable equilbrium.
|   | Cavalier    | Leon        |
| - | ----------- | ----------- |
| 1 | Madame Lisa | Madame Lisa |
| 2 | Pearl       | Pearl       |

---

|   | Madame Lisa | Pearl    |
| - | ----------- | -------- |
| 1 | Cavalier    | Leon     |
| 2 | Leon        | Cavalier |



<section>
<p>A year later...<p>
<p class="fragment">4 strangers show up in the village:</p>
<p class="fragment"> Elon, Travis, Taylor, Amee  </p>
</section>



<section>
<h3>Destroying the stability...</h3>
</section>



<section style="font-size:30px">

|   | Cavalier    | Leon        | Elon        | Travis      |
| - | ----------- | ----------- | ----------- | ----------- |
| 1 | Taylor      | Taylor      | Taylor      | Taylor      |
| 2 | Madame Lisa | Madame Lisa | Madame Lisa | Pearl       |
| 3 | Amee        | Pearl       | Amee        | Amee        |
| 4 | Pearl       | Amee        | Pearl       | Madame Lisa |

---

|   | Madame Lisa | Pearl    | Taylor   | Amee     |
| - | ----------- | -------- | -------- | -------- |
| 1 | Elon        | Elon     | Travis   | Elon     |
| 2 | Cavalier    | Leon     | Elon     | Cavalier |
| 3 | Leon        | Cavalier | Cavalier | Travis   |
| 4 | Travis        | Travis   | Leon     | Leon     |
</section>



### Algorithm

<ol>
    <li class="fragment">Each woman proposes to their no.1 choice. 
Each man rejects the ones that are not top in their lists.</li>

<li class="fragment"> Each rejected woman will propose to their next best choice.
Each man rejects the ones that are not top in their lists (free to break the previous match).</li>

<li class="fragment"> Repeat the process until everyone is matched. </li>
</ol>



<section>
<h3>Test it out</h3>
<h4 class="fragment">Round 1</h4>
<ul>
    <li class="fragment"> Elon gets letter(s) from: <span class="fragment"> Madame Lisa, Pearl, Amee </span>  </li>
    <li class="fragment"> Travis gets letter(s) from: <span class="fragment"> Taylor </span>  </li>
    <li class="fragment"> Leon and Cavalier:  <span class="fragment"> :( </span>  </li>
</ul>
<p class="fragment">Couples</p>
<p class="fragment"> Elon & Madame Lisa, Travis & Taylor  </p>
</section>



<section>
<h3>Test it out</h3>
<p class="fragment">Round 2</p>
<ul>
    <li class="fragment"> Leon gets letter(s) from:  <span class="fragment"> Pearl  </span>  </li>
    <li class="fragment"> Cavalier gets letter(s) from:  <span class="fragment"> Amee  </span>  </li>
</ul>
<p class="fragment">Couples: </p>
<p class="fragment"> Elon & Madame Lisa, Travis & Taylor, Pearl & Leon, Amee & Cavalier  </p>
<p class="fragment"> Happily Ever After!  </p>
</section>



### Other applications

<ul>
    <li class="fragment"> Residence matching </li>
    <li class="fragment"> College dorm assignments </li>
    <li class="fragment"> Kidney donation</li>
</ul>
<p class="fragment"> Gale-Shapley Algorithm. Nobel Prize in Economics in 2012. </p>



### What is mathematics?

<ul>
    <li class="fragment"> Useful </li>
    <li class="fragment"> Logical</li>
    <li class="fragment"> Creative</li>
    <li class="fragment"> Most Important: Fun </li>
</ul>


## On creativity


<iframe width="800" height="450" src=https://www.youtube.com/embed/A0WGp38PRvg frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



# Q \& A


### The mathematics 

<iframe width="800" height="450" src="https://www.youtube.com/embed/LtTV6rIxhdo?si=DeHDrtufeNcyXasr" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>