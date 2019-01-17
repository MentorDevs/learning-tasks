*MentorDevs[Stage 2] task*
> Hello again Devs, you have come far the last few tasks and this one will be a challenge but it will be worth it. Your assignment, should you choose to accept it will be :-
>
> 1. Use the provided screen shot and instructions to build a static single page website using only html5 and css in a git repository on github.
> 2. Serve the repository on github pages to serve your single page website online.
> 3. Submit your project for review when done using slack by typing, `/task github_repo_url current_stage "your_handle"`
>
>
> Good luck.

*Git and Github*
> If you do not have a github account, please create a free one. It is an important asset to developers and this is a great time to start yours.
> If you do not know git, don't worry, the most important commands are easy to learn and resources for these will be provided.
> We are also glad to answer any questions and help out to the best of our ability on any issue you face.
> We are confident that you will enjoy learning git and it will become an indispensable part of your workflow as a developer, so relax ... you got this.

*Normalize css*
> Normalize css is great for resetting css styles and helping you get a uniform cross browser design. We used it in this project and advice you do so as well.
> You can copy the styles from the github repo normalize.css file and paste them to the beginning of your styles or place them in their own css file and include that before your own styles.
> The link to the normalize css repo is here:
> https://github.com/necolas/normalize.css

*Content*
> The goal is that you will practice what you have learned in the applied visual design part.
> We also hope that by using your own content, name, introduction, projects and image as well as any other content needed you will end up with your own developer webpage.
> Thus, it is a requirement that you use your own content and not the placeholder content used in the screenshot.

*Typography*
> This project will only use the sans-serif font, set this font as well as the default size of 16px in the body tag and a text color of #333.
> The initial sizes of html headers will not be changed

*Header and navigation*
> The header markup is as follows:
>```<header class="container-wide">
  <nav>
  <a href="./" class="brand">Mentor-Devs</a>
  <span class="align-right">
    <a href="./">Blog</a>
    <a href="#contact-form">Contacts</a>
  </span>
  </nav>
</header>```
> The background color for the header tag should be set to #333.
> The font color for the navigation links should be #fdfdfd, while white can be used a light grey would be more pleasing to the eye as the contrast will not be too harsh.
> Set a margin left and right of 20px to the links in the header.
> You can replace the 'Mentor-Devs' link with your own name to personalize it further.

Tip
> Use the box sizing style on all css selectors and set it to a value of border box. This makes managing the sizes of css styled elements straight forward as margins and padding are included in the width and height pf the element.
> ``` * {
    box-sizing: border-box;
    }```

*Body*
> Set the line height to 1.5
> Set the background color to #fef89a

*Main*
>Create a main tag, the rest of the markup will be placed within this tag.

*Card*
> This design uses cards to contain information that can stand on its own.
> To create the cards, create a card class in the css.
> The card class should have a padding all round of 40px.
> The card should also have a max-width of 840px.
> Set the margins for the card class to auto.
> Set the background of the card color to #fff.
> Set a box shadow for the card with horizontal offset of zero, a vertical offset of 5px, a spread of 5px as well and a color #909090.
> Finally round off the edges of the card for a softer design using a border-radius of 10px;

*Quote*
> The quote section markup is as follows
> ```<div class="cover-and-quote">
  <div class="quote-card card">
    <p class="quote">{TODO: Replace with a quote that inspires you.}</p>
    <p class="attribution">-{TODO: Name of the person who said the quote}</p>
  </div>
</div>```
> The quote markup should be placed inside the main tag
> Style the quote paragraph to have a font size of 2.25 rem;
> Leave the attribute paragraph at the default font size of 16px set in the body attribute.
> Style the quote-card class by setting a margin of 20px to the top and bottom margins and an auto margin to left and right.
> Make the background for the the quote-card class transparent
> Finally, get rid of the box shadow for the quote-card class by adding a box shadow of none.

*Introduction*
> The introduction section markup is as follows:
>```<div class="introduction">
  <div class="card intro-card">
    <div class="bio">
      <img src="{TODO: Path to your profile picture}" class="profile" alt="{TODO: Your name}">
      <div class="name-card">
        <h1>{TODO: Your name}</h1>
        <p>{TODO: You current or desired title}</p>
      </div>
    </div>
    <div class="intro-text">
      <p>{TODO: A short description of what you do and what your skills are}</p>
    </div>
    <button type="button">Hire me!</button>
  </div>
</div>```
> Add a css class called intro-text, add a padding-bottom of 40px to this class.
> To the introduction class, add a background color of #fef89a
> Set the introduction class width to 100%.
> Add a padding bottom of 40px and a padding top of 20px to the introduction class.
> Finally, add a transform and skew the introduction class in Y direction 5 degrees.
> To correct the content skew, add the intro-card class and set a transform to it with a skew in the Y direction of -5 degrees.
> Add a margin top and bottom of 40px and margin left and right of auto to the intro-card class as well.
> Set the p tag in the div with class name-card to a color of #909090.
> For the image with the class profile, float it right and set its width to 150px.
> Set a margin right of 10px and margin-top of -120px to the profile class
> Set the border radius of the profile class to 50% to make it circular.
> Use a square for the image with dimensions above 150px with the profile class to get a circular profile photo of good quality.

*Button*
> For all button elements, apply a background color of #45bee1 and set the font color to #fff.
> Get rid of the border by setting border to none.
> Set a min height of 40px
> Set the padding to be 15px for top and bottom and 40px for left and right
> Round off the button edges by setting the border radius of the button to 5px;
> Add a box shadow to the button element for visual interest by setting its horizontal displacement to zero, it vertical displacement to 2px, its spread to 5px and finally the color to #909090.

*Project*
> The markup for the project section is as follows:
>```<div class="project">
  <div class="project-card card">
    <h2>Projects</h2>
    <!--Insert individual project cards here-->
    <div class="clear"></div>
  </div>
</div>```
> For the project class, set its background color to #a9ebef.
> Add a transform to the project class with a skew in the y direction of -5 degrees.
> Correct the content skew with setting a transform for the project-card class with a skew in the y direction of 5 degrees.
> Add a margin bottom of 40px to the project-card class.
> Set the width of the project class to 100%.
> Clear the clear class using both so that the rest of the layout is not forced to float left as the project cards.

*Project card*
> The markup for the project card is as follows:
>```<div class="single-project-card card">
  <div class="project-description">
    <h3>{TODO: Your project name}</h3>
    <p>{TODO: Your project description}</p>
  </div>
</div>```
> The project card can be used repeatedly to place different projects in the project section.
> Make sure that all the projects you place come before the div with the clear class so that the float on the project card does not affect the rest of the layout.
> To style to the single-project-card class, set its width to 48%, float it left, add a margin right of 10px, set its min height to 460px or whatever value you will need to ensure all project cards are of equal height.
> Keep the project description short between 2 - 4 lines so that the project cards are not disproportionately long.
> Get rid of the box shadow in the single-project-card class by setting its box shadow to none.
> Add a solid border to the single-project-card class of 1px and color #f0f0f0. Set the padding of the class to 0 and give it a position of relative.
> To the project-description class, set a padding of 40px, set its position to absolute, set it bottom value to 0 and background to #fff.
> For each project card, set its background image to an image of your project with a background size of cover. Set the background repeat to no repeat.
> Use as many project cards as you have projects that you want to show.

*Contact form*
> The markup for contact form section is as follows:
>```<div id="contact-form" class="contact-form">
  <div class="contact-form-card card">
    <h2>Contact me</h2>
    <p>Will be glad to here from you</p>
    <form action="./">
      <div class="input-group half"> 
        <label for="name">Name</label>
        <input type="text" name="name" id="name">
      </div>
      <div class="input-group half last">
        <label for="email">Email</label>
        <input type="email" name="email" id="email">
      </div>
      <div class="input-group text-area clear">
        <label for="message" hidden>Message</label>
        <textarea name="message" id="message" placeholder="I would like..."></textarea>
      </div>
      <button type="submit">Send</button>
    </form>
  </div>
  <p class="stand-alone">You can also reach me through my email, {TODO: Place your email}. See other stuff I work on my <a href="{TODO: Place a link to your github}">github.</a></p>
</div>```
> For the contact-form class, set its background color to #f5b4fe, its width to 100%, give it a padding bottom of 40px and a padding top of 20px.
> Add a skew to the contact form class in the y direction of 5 degrees.
> To correct the content skew, add a skew in the y direction on the contact-form-card and stand-alone classes of -5 deg.
> Add a margin of 40px for the bottom margin and auto for left and right to both classes. Set the top margin to 0 for the contact-form-card class.
> To the input group class, add a margin top and bottom of 20px .
> To an element with both the input group class and half class, set its width to 49% and float it left.
> To an element with both input group AND clear classes, set its top padding to 20px.
> For the input and textarea elements, set their min height to 40px.
> For input elements, set their border to none, background to #f0f0f0 and give them a margin-left and padding-left of 20px.
> For the text area element, set its width to 100%, its height to 50px, it border to none, then give it a border bottom that is solid, 1px and has a color of #f0f0f0.
> Finally for the stand-alone class, make its max width 840px, set its top and bottom margins to 40px and its left and right margins to auto. Then give it a padding of 40px.
