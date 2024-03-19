<h1>Bootstrap 4 Drills</h1>
<p>The purpose of this lab is to practice pulling in Bootstrap 4's CDN and use its class based styling.</p>
<h2>Steps</h2>
<h4>Setup</h4>
<ol>
<li>Create a new folder for these drills, title it Bootstrap 4 Drills</li>
<li>Go ahead and initialize a git repository on this project so it will be available to view on your github account.</li>
<li>Create a <code>README.md</code> file, copy and past these drill instructions into that file.</li>
<li>Create an <code>index.html</code> page, use the keyboard shortcut to get the html doc started.</li>
<li>Go to the following <a href="https://getbootstrap.com/docs/4.0/getting-started/introduction/" target="_blank">link</a> copy the CDN link and past it in the head of your html document.</li>
<li>You now have connected the Bootstrap CDN to your project and can begin using Bootstrap 4! Hooray.</li>
<li>Add a <code>styles.css</code> document, link it to your html document AFTER the bootstrap link.</li>
</ol>
<h4>Containers and the Grid System</h4>
<ol>
<li>Add a div to your html document, using bootstraps container class, have this be a container.</li>
<li>To visually see what a container class does to a div, we will need to apply some styling to it in CSS. Let’s go to our CSS document and apply a background-color of blue and a height of 500px to anything with a class named container (Which for now should only be 1 element).</li>
<li>Change the class on the div from a container to a container-fluid.  Don't forget to change your CSS selector to container-fluid as well! Refresh and take not of the differences. Once you are finished visually seeing the difference between the two, remove or comment out the styling in the CSS file.</li>
<li>Change the container-fluid back to container.</li>
<li>Insert a div inside of the existing container div. Give this div a class name of row, then insert an h1 element inside of the row div. Have the text read “First Boostrap Project”.</li>
<li>Refer to this <a href="https://getbootstrap.com/docs/4.0/layout/grid/" target="_blank">link</a> on the grid system to learn how rows and alignment work using bootstrap.</li>
<li>Lets try to center align our h1! Go to the previous link to explore how to do so.
<ul>
<li><strong>Hint</strong>: Jump to the <a href="https://getbootstrap.com/docs/4.0/layout/grid/#horizontal-alignment" target="_blank">horizontal alignment section</a> of bootstraps documents</li>
</ul></li>
<li>Add a new div with class <code>row</code> beneath the other row div, this will be another "section" row of elements. Add 3 divs within the row, give each some text of your choice and apply bootstrap styling to have 1 div appear at the start of the row, one in the center, and one at the end.</li>
</ol>
<h4>Bootstrap Forms</h4>
<ol>
<li>Use this <a href="https://getbootstrap.com/docs/4.0/components/forms/" target="_blank">link</a> for reference for the next section:</li>
<li>Create another div class row beneath the previous row.</li>
<li>Create a form inside of the existing container and your newly created row.</li>
<li>Have this form contain an input for an email and password. Make sure each input has labels!</li>
<li>Add 2 checkboxes to the form, one for cats and one for dogs.</li>
<li>Add 3 radios, have them say Cheese Pizza, Hawaiian Pizza, and Supreme Pizza.</li>
<li>Make Sure the form has a submit input!</li>
<li>Your page should like somewhat close to <a href="https://gravity-store.covalence.io/files/201939-1651405374603879-resource.jpg" target="_blank">this, with your text being different.</a></li>
<li>Add a col class of size 12 to your form element.</li>
<li>Add a border of color primary to your form element.
<ul>
<li><strong>Hint</strong>:  Use <a href="https://getbootstrap.com/docs/4.0/utilities/borders/" target="_blank">Bootstrap classes</a>!</li>
</ul></li>
<li>Add a padding of 3 to your form using Bootstrap <a href="https://getbootstrap.com/docs/4.0/utilities/spacing/" target="_blank">utilities</a>.</li>
<li>After some styling, your form should resemble something like <a href="https://gravity-store.covalence.io/files/201939-1694657129183191-resource.jpg" target="_blank">this masterpiece</a>.</li>
</ol>
<h4>Cards</h4>
<ol>
<li>Refer to <a href="https://getbootstrap.com/docs/4.0/components/card/" target="_blank">this link</a> for more information on cards.</li>
<li>Beneath the previous row div, but inside the container, create a another row div.</li>
<li>Within the new row, create a basic card with a card body and have it have an h3 which will be a friends name, and a paragraph element containing a small piece of info on your friend. Create 6 of these cards.
<ul>
<li>Your cards should be stacked vertically and only be as wide as the amount of text in your paragraph, <a href="https://gravity-store.covalence.io/files/201939-1805228098644687-resource.jpg" target="_blank">something like this</a>.</li>
</ul></li>
<li>Have them align so there are 2 per row.
<ul>
<li><strong>Hint</strong>: Use <a href="https://getbootstrap.com/docs/4.0/layout/grid/#grid-options" target="_blank">Bootstrap's <code>col</code> system to make the cards 2 per row</a>.</li>
<li>It should look like <a href="https://gravity-store.covalence.io/files/201939-1832231432105396-resource.jpg" target="_blank">this example</a>.</li>
</ul></li>
<li>Once you get them aligning 2 per row, change it so it is 3 per row.
<ul>
<li>Like <a href="https://gravity-store.covalence.io/files/201939-1834571217646562-resource.jpg" target="_blank">this example</a>.</li>
</ul></li>
</ol>
<p>Noice!  Let's go practice some more Bootstrap by recreating a resume design.</p>