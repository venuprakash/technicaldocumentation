<h1>Technical Documentation</h1>

<h3>https://venuprakash.github.io/technicaldocumentation/</h3>

<h3>Objective</h3>
<h4>Build a Technical Documentation Page</h4>

<h3>User Stories:</h3>
<ol>
<li>You can see a main element with a corresponding id="main-doc", which contains the page's main content (technical documentation)</li>
<li>Within the #main-doc element, you can see several section elements, each with a class of main-section. There should be a minimum of five</li>
<li>The first element within each .main-section should be a header element, which contains text that describes the topic of that section.</li>
<li>Each section element with the class of main-section should also have an id that corresponds with the text of each header contained within it. Any spaces should be replaced with underscores (e.g. The section that contains the header "JavaScript and Java" should have a corresponding id="JavaScript_and_Java")</li>
<li>The .main-section elements should contain at least ten p elements total (not each)</li>
<li>The .main-section elements should contain at least five code elements total (not each)</li>
<li>The .main-section elements should contain at least five li items total (not each)</li>
<li>You can see a nav element with a corresponding id="navbar"</li>
<li>The navbar element should contain one header element which contains text that describes the topic of the technical documentation</li>
<li>Additionally, the navbar should contain link (a) elements with the class of nav-link. There should be one for every element with the class main-section</li>
<li>The header element in the #navbar must come before any link (a) elements in the navbar</li>
<li>Each element with the class of nav-link should contain text that corresponds to the header text within each section (e.g. if you have a "Hello world" section/header, your navbar should have an element which contains the text "Hello world")</li>
<li>When you click on a navbar element, the page should navigate to the corresponding section of the #main-doc element (e.g. If you click on a .nav-link element that contains the text "Hello world", the page navigates to a section element with that id, and contains the corresponding header)</li>
<li>On regular sized devices (laptops, desktops), the element with id="navbar" should be shown on the left side of the screen and should always be visible to the user</li>
<li>Your technical documentation should use at least one media query</li>
  </ol
<p>Fulfill the user stories and pass all the tests below to complete this project. Give it your own personal style. Happy Coding!</p>

<code><strong>Note:</strong> Be sure to add <link rel="stylesheet" href="styles.css"> in your HTML to link your stylesheet and apply your CSS</code>

<h3>Tests</h3>
<ul>
<li>Passed:You should have a main element with an id of main-doc.</li>
<li>Passed:You should have at least five section elements with a class of main-section.</li>
<li>Passed:All of your .main-section elements should be section elements.</li>
<li>Passed:You should have at least five .main-section elements that are descendants of #main-doc.</li>
<li>Passed:The first child of each .main-section should be a header element.</li>
<li>Passed:None of your header elements should be empty.</li>
<li>Passed:All of your .main-section elements should have an id.</li>
<li>Passed:Each .main-section should have an id that matches the text of its first child, having any spaces in the child's text replaced with underscores (_) for the id's.</li>
<li>Passed:You should have at least 10 p elements (total) within your .main-section elements.</li>
<li>Passed:You should have at least five code elements that are descendants of .main-section elements.</li>
<li>Passed:You should have at least five li elements that are descendants of .main-section elements.</li>
<li>Passed:You should have a nav element with an id of navbar.</li>
<li>Passed:Your #navbar should have exactly one header element within it.</li>
<li>Passed:You should have at least one a element with a class of nav-link.</li>
<li>Passed:All of your .nav-link elements should be anchor (a) elements.</li>
<li>Passed:All of your .nav-link elements should be in the #navbar.</li>
<li>Passed:You should have the same number of .nav-link and .main-section elements.</li>
<li>Passed:The header element in the #navbar should come before any link (a) elements also in the #navbar.</li>
<li>Passed:Each .nav-link should have text that corresponds to the header text of its related section (e.g. if you have a "Hello world" section/header, your #navbar should have a .nav-link which has the text "Hello world").</li>
<li>Passed:Each .nav-link should have an href attribute that links to its corresponding .main-section (e.g. If you click on a .nav-link element that contains the text "Hello world", the page navigates to a section element with that id).</li>
<li>Passed:Your #navbar should always be on the left edge of the window.</li>
<li>Passed:Your Technical Documentation project should use at least one media query.</li>
</ul>
