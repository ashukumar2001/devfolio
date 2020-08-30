# devfolio
devfolio is portfolio website template for developers to show there skills, projects and about. 


## Features

⚡️ Modern UI Design\
⚡️ One Page Layout\
⚡️ Full Responsive\
⚡️ Styled with Custom CSS3\
⚡️ Easily Customizable

To view a demo example, **[click here](https://ashukumar2001.github.io/devfolio/)**\
To view a live example, **[click here](https://ashukumar2001.github.io/)**

---

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## How To Use 🔧

From your command line, first clone devfolio:

```bash
# Clone this repository
$ git clone https://github.com/ashukumar2001/devfolio.git

# Go into the repository
$ cd devfolio/

# Remove current origin repository
$ git remote remove origin
```

---

## Instructions:

### Step 1 - STRUCTURE

Go to `index.html` and fill your information, they are 4 sections:

### About Section
* On `img` tag fill the ```src``` with your profile picture must be located in ```images/``` folder.
* On `h3.about-me-item` add your custom name.
* On `button.resume` add your custom button.

```html
<!-- About section -->
        <section id="about" class="main-item">
            <div class="container" id="about-container">
                <div id="about-wrapper">
                    <img src="images/my-image.png" alt="" id="myImage" class="about-item">
                    <div id="about-me" class="about-item">
                        <h3 class="about-me-item">Hi, I am Your Name.</h3>
                        <p class="about-me-item">I am UNKNOWN developer.</p>
                        <p class="about-me-item">I am passionate about building scalable software, creating effective
                            solutions, and learning every day to grow professionally in the IT field.</p>
                        <button class="resume btn">CUSTOM BUTTON</button>
                    </div>
                </div>
            </div>
        </section> <!-- About Section end here -->
```

### Projects Section
* On ```img``` tag fill the ```src``` with your project image must be located in ```images/``` folder.
* On `h3.p-heading` add your Custom Project Name.
* On `p.p-description` add you Custom Project Description.
* after filling details about your project paste the code into the `<ul class="glide__slides">` to add your new project.

```html
<!-- Project Section -->
<li class="glide__slide">
  <div class="project-wrapper">
     <img src="images/YOUR-IMAGE.jpg" alt="">
     <div class="project-about">
          <h3 class="p-heading">Project Heading</h3>
          <p class="p-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque est nobis quos quae qui quas
              asperiores inventore odio iusto praesentium consequuntur magnam, impedit eaque
              ecessitatibus, accusantium maxime? Mollitia, a exercitationem.
          </p>
      </div>                           
   </div> 
 </li>   <!-- Project Section End Here -->
```

### Skills Section
* On ```span.heading``` add your custom skills.

```html
<!-- Skills Section -->
 <section id="skills" class="main-item">
   <div class="container" id="skills-container">
     <div class="languages">
        <span class="heading">Front-end</span>
            <i class="fab fa-js"></i>
            <i class="fab fa-html5"></i>
            <i class="fab fa-css3"></i>
     </div>
     <div class="languages">
             <span class="heading">Back-end</span>
             <i class="fab fa-node"></i>
     </div>
     <div class="languages">
             <span class="heading">Tools</span>
             <i class="fab fa-git"></i>
     </div>
   </div>
 </section> <!-- Skills Section end here -->
```

### Contact Section
* On `a.contact-button` fill `href` attribute with your contact details.
* On `a.social-item` fill `href` attribute with your social accounts link.
* On `<i class="">` fill `class` attribute with your required icon form Font Awesome.
* You can delete or add as many `a` links your want.

```html
<!-- contact section -->
        <section id="contact" class="main-item">
            <div class="container" id="contact-container">
                <h2>Would you like to work with me? Awesome!!!</h2>
                <div id="contact-button-container">
                    <a href="mailto:xyz@gmail.com" class="contact-button btn">Email me</a>
                    or
                    <a href="tel:+0123456789" class="contact-button btn">Call me</a>
                </div>
                <div id="social-container" class="contact-container-item">
                    <a href="#" class="social-item">
                        <i class="fab fa-github social-icon"></i>
                    </a>
                    <a href="#" class="social-item">
                        <i class="fab fa-linkedin-in social-icon"></i>
                    </a>
                    <a href="#" class="social-item">
                        <i class="fab fa-instagram social-icon"></i>
                    </a>
                </div>
            </div>
        </section><!-- Contact Section end here -->
```

### Step 2 - STYLES

Change the color theme of website.

Go to `style/style.css` and only change the values of this properties.

```css
:root {
    font-size: 15px;
    font-family: 'Montserrat', sans-serif;
    --dark-background: rgb(0, 0, 0);
    --dark-text: white;
    --light-background:rgb(255, 255, 255);
    --light-text: rgb(0, 0, 0);
    --about-background: linear-gradient(to right,rgb(132, 243, 255), rgb(5, 200, 194));
    --project-background: linear-gradient(to right,rgb(115, 255, 176), #55ee71);
    --skill-background: rgb(168, 217, 255);
    --contact-background: rgb(255, 250, 162);
    --dark-border: rgb(255, 255, 255);
    --light-border: rgb(0, 0, 0);
    --transition-fast: 300ms;
    --transistion-slow: 600ms;
}
```

---

## Technologies used 🛠️

- [Glider.js](https://glidejs.com/) - A dependency-free JavaScript ES6 slider and carousel.

## Authors

- **Ashu Kumar** - [https://github.com/ashukumar2001](https://github.com/ashukumar2001)

