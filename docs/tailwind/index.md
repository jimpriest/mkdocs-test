# TailwindCSS Implementation for ColdFusion Code
================================================

- [Introduction](#introduction)
	- [Benefits](#benefits)
	- [Drawbacks](#drawbacks)


## Introduction
Tailwind CSS works by scanning all of our HTML files, JavaScript components, and any other templates for class names, generating the corresponding styles and then writing them to a static CSS file: `tailwind.min.css`.

Tailwind works by writing pre-defined tailwind classes in the html element class. Ie, the following snippet automatically generates a good bit of css. 
- [Test This code.](https://play.tailwindcss.com/RmjTFriaL3)
```
<h1 class="p-5 italic font-bold bg-blue-300"> My Title </h1>
```

Automatically generated css:
```
h1 {
	font-weight: 700;
	font-style: italic;
	padding: 1.25rem/* 20px */;
	--tw-bg-opacity: 1;
	background-color: rgb(147 197 253 / var(--tw-bg-opacity));
}
```

### Benefits
The first immediate benefits of tailwind, are that you are able to generate some pretty complex components with no custom CSS by utilizing those tailwind specific classes in an html element. This actually works best with a Javascript Front End Framework(reactjs, vuejs, etc...) where you would write a javascript component and define it with those styles then reuse that component anywhere you needed.

### Drawbacks
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas tempor massa in urna vestibulum, et blandit arcu congue. Praesent ac elit vehicula, malesuada arcu vel, pulvinar orci. Sed quis feugiat dolor, sit amet eleifend massa. Fusce aliquam magna in tempor pellentesque. Maecenas ut eros porttitor, tincidunt augue ut, volutpat felis. Nulla tortor lectus, congue at justo ac, viverra commodo mauris. Curabitur ante lacus, aliquet a velit in, consequat congue turpis. 