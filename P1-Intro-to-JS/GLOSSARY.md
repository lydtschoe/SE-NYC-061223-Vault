<h1 align="center"><b><big>G</big>LOSSARY:</b> <big>P</big>HASE <big>1</big></h1>

<h2 align="left"><b><big>S</big>UMMARY</b></h2>

<p align="left">This section serves as the living dictionary and terminological reference guide for concept terms and coding topics covered in Phase 1 of Flatiron School's Software Engineering curriculum.</p>

<p align="left"><b>This version of the Glossary is curated for the <big>SE-NYC-061223</big> cohort.</b></p>

<p align="left">At any time, students are welcome and encouraged to submit pull requests and suggest updates to this resource to better serve current and future generations of Flatiron School engineering students.</p>

<p align="left"><b>This phase covers the following major content areas:</b></p>
<ul>
    <li><b><big>G</big>ENERAL <big>P</big>ROGRAMMING</b></li>
    <li><b><big>I</big>NTRODUCTORY <big>W</big>EB <big>D</big>EVELOPMENT</b></li>
    <li><b><big>E</big>VENT <big>H</big>ANDLING</b></li>
    <li><b><big>S</big>ERVER <big>C</big>OMMUNICATION</b></li>
</ul>

Materials and information (including concept terms and coding topics) critical-to-know for the phase-specific coding challenge are _denoted by italicized text_. 

---

<h2 align="center"><b><big>G</big>ENERAL <big>P</big>ROGRAMMING</b></h2>

<h3 align="left"><big>C</big>ONCEPT <big>T</big>ERMS</h3>

| <big>T</big>ERM | <big>D</big>EFINITION | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| ***Variable*** | A value or object that stores some information that can be used at some later point. | `var myVariable = 0` |
| ***Variable*** | ↳ | `let anotherVariable = 1` |
| ***Variable*** | ↳ | `const yetAnotherVariable = 2` |
| ***Function*** | A chunk of coding instructions designed to be executed at some later point in time. | `function myNamedFunction () { ... }` |
| ***Function*** | ↳ | `const myNamedArrowFunction = () => { ... }` |
| ***Method*** | A function uniquely "owned" by a specific object or data structure. | `element.someMethod()` |
| ***Array*** | A list-like representation of data that can be iterated across. | `let myArray = [1, 2, 3]` |
| ***Object*** | An abstract model that's used to structure a program and its relevant data and/or instructions to be more modular and reusable. | `let myObject = { greeting: "Hello World" }`

---

<h2 align="center"><b><big>I</big>NTRODUCTORY <big>W</big>EB <big>D</big>EVELOPMENT</b></h2>

<h3 align="left"><big>C</big>ONCEPT <big>T</big>ERMS</h3>

| <big>T</big>ERM | <big>D</big>EFINITION | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| ***HTML*** | (**H**yper-**T**ext **M**arkup **L**anguage) A language-like coding syntax that defines the structure and content of web page; it's comprised of elements that are best represented in a tree-like structure. | `<div><h1>Hello World!</h1></div>` |
| ***CSS*** | (**C**ascading **S**tyle **S**heets) A language-like coding syntax that manipulates HTML by defining the layout and style of HTML elements. | `body { background-color: black; }`
| ***JavaScript*** | A programming language that is used to dynamically interact with web pages by instructing changes to the defining HTML, CSS, and elements of a target page. | `console.log("Hello World!")` |
| ***DOM*** | (**D**ocument **O**bject **M**odel) An abstract model organized like a tree that captures the hierarchy of elements in a web page and defines the medium by which JavaScript communicates with a web page. | N/A. |

<h3 align="left"><big>C</big>ODING <big>T</big>OPICS</h3>

| <big>T</big>OPIC | <big>S</big>UMMARY | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| *`index.html`* | ... | N/A. |
| *`style.css`* | ... | N/A. |
| `app.js` or *`index.js`* | ... | N/A. |
| *`.querySelector()`* | ... | `let myButton = document.querySelector("#my-button")` |
| *`.querySelectorAll()`* | ... | `let titles = document.querySelectorAll("p")` |
| *`.createElement()`* | ... | `const newImage = document.createElement("img")` |
| *`.getElementById()`* | ... | `document.getElementById("my-text").style.color = "red";` |
| `.getElementsByClassName()` | ... | `let myButtons = document.getElementsByClassName("my-button")` |
| *`.appendChild()`* | ... | `myCard.appendChild(newImage)` |
| *`.remove()`* | ... | `myButton.remove()` |

---

<h2 align="center"><b><big>E</big>VENT <big>H</big>ANDLING</b></h2>

<h3 align="left"><big>C</big>ONCEPT <big>T</big>ERMS</h3>

| <big>T</big>ERM | <big>D</big>EFINITION | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| *Events* | ... | N/A. |
| *Click Events* | ... | N/A. |
| *Submit Events* | ... | N/A. |
| Hover Events | ... | N/A. |
| Event Propagation | ... | N/A. |
| Event Capturing | ... | N/A. |
| Event Targeting | ... | N/A. |
| Event Bubbling | ... | N/A. |

<h3 align="left"><big>C</big>ODING <big>T</big>OPICS</h3>

| <big>T</big>OPIC | <big>S</big>UMMARY | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| *`preventDefault()`* | ... | ... |
| *`.addEventListener()`* | ... | ... |

---

<h2 align="center"><b><big>S</big>ERVER <big>C</big>OMMUNICATION</b></h2>

<h3 align="left"><big>C</big>ONCEPT <big>T</big>ERMS</h3>

| <big>T</big>ERM | <big>D</big>EFINITION | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| *Client* | ... | N/A. |
| *Server* | ... | N/A. |
| *HTTP Verbs* | ... | N/A. |
| *GET Requests* | ... | N/A. |
| POST Requests | ... | N/A. |
| PATCH Requests | ... | N/A. |
| DELETE Requests | ... | N/A. |

<h3 align="left"><big>C</big>ODING <big>T</big>OPICS</h3>

| <big>T</big>OPIC | <big>S</big>UMMARY | <big>E</big>XAMPLE |
| :--- | :--: | ---: |
| *`fetch()`* | ... | ... |
| *`.then()`* | ... | ... |

---

