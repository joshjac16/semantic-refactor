# semantic-refactor
## A study in refactoring HTML semantically 
Semantic refactoring is the process changing code of a program in a way that it does not alter the function of the code but it improves the internal structure of the source code and make it easier for screen readers to understand 

This project was intended to show how sematic refactoring can make a code look more appealing which in-turn makes it easier to read for developers and AI screenreaders 

The code was given to us in a very bland and unordered way and our goal was to edit the CSS file and the index.html source code to make it more semantic 

an example on how it was done is below 

## Given code 
<!-- <div class="header"> 
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
           <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
@@ -22,61 +22,62 @@ <h1>Hori<span class="seo">seo</span>n</h1>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div> -->

## Edited code
 <!-- <header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
@@ -22,61 +22,62 @@ <h1>Hori<span class="seo">seo</span>n</h1>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        <nav>
    </header> -->
