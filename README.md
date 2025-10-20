# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Desktop](/Screenshot.png)
![Mobile](/Screenshot2.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/DevouraStudio/Summary-Results-Project)
- Live Site URL: [Add live site URL here](https://devourastudio.github.io/Summary-Results-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap Grid System And Responsiveness Breakpoints
- Desktop-first workflow
- CSS Media Queries
- [Bootstrap](https://getbootstrap.com/) - CSS Framework

### What I learned

"Although this project presented numerous challenges and difficulties, it was ultimately completed successfully. One of the main challenges involved creating the numerical circle that represented the final score. Thanks to Bootstrap, this feature was no longer a significant issue in HTML; however, developing that circle provided me with valuable personal lessons.

Most of the challenges I faced were related to the styling language, CSS, which even led me to rewrite the entire CSS code twice during development. Using Bootstrap’s grid system in this project was particularly frustrating for me, as it frequently caused layout issues while writing the CSS file.

Ensuring the design’s responsiveness also required more time than in my previous projects, as I needed to adjust the size properties of several elements. Overall, this project was more complex than my earlier ones, but it reinforced an important belief — that with persistence, anything is possible."

```html
<div class="container" id="Num-Div">
	<span id="Num">76</span>
	<span id="Num2">of 100</span>
</div>
```
```css
@media (min-width: 375px) and (max-width: 1200px) {
	body {
		padding-bottom: 4rem;
	}

	div.card {
		width: 26rem;
		height: 64rem;
	}

	div.row {
		margin: 0;
	}

	#First-Col {
		width: 26rem;
		height: 32rem;
	}

	#Second-Col {
		width: 26rem;
		height: 32rem;
		padding-right: 0;
	}

	p.lead {
		margin-top: 0.5rem;
		letter-spacing: normal;
		padding-right: 1rem;
		padding-left: 1rem;
		text-align: center justify;
	}

	h1.h1 {
		padding-top: 1rem;
		padding-left: 0.5rem;
	}

	#First-Alert,
	#Second-Alert,
	#Third-Alert,
	#Forth-Alert {
		margin-left: 0.5rem;
	}
}
```

### Continued development

"In the future, I plan to make greater use of the Bootstrap grid system in my projects in order to fully understand its core principles and strengths. Through my research on other front-end web development projects, I have realized how effectively the grid system — and even Flexbox — can help organize and coordinate the layout of elements on web pages.

I also intend to work on more advanced and complex projects in the near future, particularly those that involve the use of JavaScript."
### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - "During This Project, I Frequently Referred to the Mozilla Developer Network (MDN) Website as a Trusted Resource for Learning and Clarifying HTML, CSS, and JavaScript. MDN Provided Clear Documentation, Practical Examples, and Best Practices That Helped Me Solve Challenges More Efficiently. Using MDN Not Only Improved My Technical Accuracy but Also Strengthened My Confidence in Applying Modern Web Standards to My Work."

- [ChatGPT](https://www.chatgpt.com/) - "Throughout This Project, I Benefited Greatly From the Guidance and Support Provided by ChatGPT. From Explaining Complex HTML, CSS, and Bootstrap Concepts to Offering Practical Code Examples and Debugging Advice, ChatGPT Helped Me Overcome Challenges More Efficiently. It's Clear Explanations and Creative Suggestions Played a Key Role in Improving My Skills, Building My Confidence, and Ensuring the Project’s Overall Quality."

- [Bootstrap](https://getbootstrap.com/) - "In This Project, I Utilized Bootstrap to Streamline the Design Process and Enhance the Visual Appeal of My Pages. By Leveraging Bootstrap’s Pre-Built Components, Utility Classes, and Customization Options, I Was Able to Maintain Consistent Styling, Organize Content Effectively, and Apply Modern Web Design Techniques More Efficiently. Using Bootstrap Helped Me Focus on Creativity and Attention to Detail While Building the Project."

## Author

- Website - [DevouraStudio](https://www.devoura.ir)
- Frontend Mentor - [@DevouraStudio](https://www.frontendmentor.io/profile/DevouraStudio)
- Dribble - [@DevouraStudio](https://www.dribbble.com/DevouraStudio)
- Github - [@DevouraStudio](https://www.github.com/DevouraStudio)
- Codepen - [@DevouraStudio](https://www.codepen.io/DevouraStudio)
