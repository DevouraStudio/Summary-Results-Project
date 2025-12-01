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

### The challenge:

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshots:

![Desktop](/Screenshot.png)
![Mobile](/Screenshot2.png)

### Links:

- Solution URL: [solution URL](https://github.com/DevouraStudio/Summary-Results-Project)
- Live Site URL: [live site URL](https://devourastudio.github.io/Summary-Results-Project/)

## My process

### Built with:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap Grid System And Responsiveness Breakpoints
- Desktop-first workflow
- CSS Media Queries
- [Bootstrap](https://getbootstrap.com/) - CSS Framework

### What I learned:

"Although This Project Presented Numerous Challenges And Difficulties, It Was Ultimately Completed Successfully. One Of The Main Challenges Involved Creating The Numerical Circle That Represented The Final Score. Thanks To Bootstrap, This Feature Was No Longer A Significant Issue In HTML; However, Developing That Circle Provided Me With Valuable Personal Lessons.

Most Of The Challenges I Faced Were Related To The Styling Language, CSS, Which Even Led Me To Rewrite The Entire CSS Code Twice During Development. Using Bootstrap’s Grid System In This Project Was Particularly Frustrating For Me, As It Frequently Caused Layout Issues While Writing The CSS File.

Ensuring The Design’s Responsiveness Also Required More Time Than In My Previous Projects, As I Needed To Adjust The Size Properties Of Several Elements. Overall, This Project Was More Complex Than My Earlier Ones, But It Reinforced An Important Belief — That With Persistence, Anything Is Possible."

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

### Continued development:

"In The Future, I Plan To Make Greater Use Of The Bootstrap Grid System In My Projects In Order To Fully Understand Its Core Principles And Strengths. Through My Research On Other Front-End Web Development Projects, I Have Realized How Effectively The Grid System — And Even Flexbox — Can Help Organize And Coordinate The Layout Of Elements On Web Pages.

I Also Intend To Work On More Advanced And Complex Projects In The Near Future, Particularly Those That Involve The Use Of JavaScript."

### Useful resources:

- [MDN](https://developer.mozilla.org/en-US/) - "During This Project, I Frequently Referred to the Mozilla Developer Network (MDN) Website as a Trusted Resource for Learning and Clarifying HTML, CSS, and JavaScript. MDN Provided Clear Documentation, Practical Examples, and Best Practices That Helped Me Solve Challenges More Efficiently. Using MDN Not Only Improved My Technical Accuracy but Also Strengthened My Confidence in Applying Modern Web Standards to My Work."

- [ChatGPT](https://www.chatgpt.com/) - "Throughout This Project, I Benefited Greatly From the Guidance and Support Provided by ChatGPT. From Explaining Complex HTML, CSS, and Bootstrap Concepts to Offering Practical Code Examples and Debugging Advice, ChatGPT Helped Me Overcome Challenges More Efficiently. It's Clear Explanations and Creative Suggestions Played a Key Role in Improving My Skills, Building My Confidence, and Ensuring the Project’s Overall Quality."

- [Bootstrap](https://getbootstrap.com/) - "In This Project, I Utilized Bootstrap to Streamline the Design Process and Enhance the Visual Appeal of My Pages. By Leveraging Bootstrap’s Pre-Built Components, Utility Classes, and Customization Options, I Was Able to Maintain Consistent Styling, Organize Content Effectively, and Apply Modern Web Design Techniques More Efficiently. Using Bootstrap Helped Me Focus on Creativity and Attention to Detail While Building the Project."

## Author

- Website - [DevouraStudio](https://www.devoura.ir)
- Frontend Mentor - [@DevouraStudio](https://www.frontendmentor.io/profile/DevouraStudio)
- Github - [@DevouraStudio](https://www.github.com/DevouraStudio)
- Codepen - [@DevouraStudio](https://www.codepen.io/DevouraStudio)
