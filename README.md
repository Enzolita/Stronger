# Stronger
![Responsive view of Stronger-Project on all devices](https://github.com/Enzolita/Stronger/blob/main/documentation/responsive.png)
### For this project I've created a website for a gym called Stronger that's based in Stockholm Sweden.
### This website is created mainly for people who want to make a change their lifestyle and for those who love fitness and to join a community with people who share the same interest.
### The target audience for this website will be people looking to get into fitness or are currently already working out.
[The live link can be found here](https://enzolita.github.io/Stronger/index.html)
---

# Design

 **Fonts**

I chose to opt for the Raleway and Poppins fonts for this project and few reasons why they stood out to me,
- Readability - I found both fonts ensured the content remained easy to read an digest across all resolutions.
- Versatility - Raleway and Poppins adapt well to various contexts without sacrificing readability.
- Distinctiveness - Raleway font came across very elegant and refined, whereas Poppins contributes a more friendly and approachable vibe.

**Images**

I used some free source images from Pexels for multiple reasons,
- Firstly, these images provide visual context and evoke a sense of activity and fitness, aligning perfectly with the theme or content of the project.
- Secondly, by choosing high-quality images from Pexels, I ensure a professional and polished appearance, enhancing the overall aesthetic appeal of the project.
- Finally, I chose images that I felt would resonate with my audience, whether showcasing workout routines via video or personnel.

**Colors**

- I used the color orange as main representation for the brand Stronger.
- Black and white were used across the project primarily for text or to improve readability.
- Finally text shadow was used across the project in moments were contrast was an issue for example light background and light color text.


# Features

**Navbar**

  - A fully responsive navigation bar that that allows users to navigate to other page in the website, with a hover effect on the current active page. The main logo also acts as a second link to allow to user to return back to the home page.


  <details><summary>Navbar Screenshot</summary>

  ![Project navbar large](https://github.com/Enzolita/Stronger/blob/main/documentation/nav-large.png)
  ![Project navbar small](https://github.com/Enzolita/Stronger/blob/main/documentation/nav-small.png)
  </details>

**About Us**

  - A page that provides the user with information about the gym and community.

  <details><summary>About Us Screenshot</summary>

  ![About us](https://github.com/Enzolita/Stronger/blob/main/documentation/about-us.png)

  </details>

**Sign Up**

  - An interactive sign up form to enable users to get in touch with the company by signing up and recieving an email.
  - Includes fields for name and email.
  - On successfull submission the users redirect to a thank you page in order to provide feedback to the user.

  <details><summary>Sign Up Form Screenshot</summary>

 ![Sign up](https://github.com/Enzolita/Stronger/blob/main/documentation/signup-form.png)

  </details>

**The Footer**

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user.
  - The footer is valuable to the user as it encourages them to keep connected via social media.

  <details><summary>Footer Screenshot</summary>

  ![Footer](https://github.com/Enzolita/Stronger/blob/main/documentation/footer.png)

  </details>

# Manual Testing

## Feature Testing

**Navbar**

  - Click on each navigation link to make sure that the correct page is showing and redirected to.
  - Mouse over hover effect when hovering on a navigation link.
  - Navbar is sticky to top of page when scrolling down.
  - Active page has a text decoration effect to indicate to the user which page they are on.
  - Check responsiveness on navigation bar on different resolutions.

**Footer**

- Footer is sticky to the bottom of the page.
- The social media links take the user to the correct social media page but also opens up in a new tab.

**Sign up Form**

- Make sure empty form can't be submitted.
- Make sure the input field have the correct type and show html browser error.
- When the form is correctly filled in, the user is correctly directed to the submit.html page.

**Call to action buttons**

- Make sure all buttons are redirecting the user to the correct page.

## Responsiveness

 - I leveraged the developer tools to test the responsiveness of the project across different resolutions.

## Lighthouse Testing

**Home Page Results**

![Lighthouse results for Home Page](https://github.com/Enzolita/Stronger/blob/main/documentation/lh-home.png)

**About Us Page Results**

![Lighthouse results for About Page](https://github.com/Enzolita/Stronger/blob/main/documentation/lh-about.png)

**Sign Up Page Results**

![Lighthouse results for Sign Up page](https://github.com/Enzolita/Stronger/blob/main/documentation/lh-signup.png)

**Submit Page Results**

![Lighthouse results for Submit page](https://github.com/Enzolita/Stronger/blob/main/documentation/lh-submit.png)

**Known Issues**
- The footer on the about us page and sign up page does not match the home and submit page.

#### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)
  - All html pages were checked.
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)
  - There is one warning relating to the imported css stylesheet and this is related to imported stylesheets not being checked in direct input or file upload modes.

## Deployment

**Manual Deployment**

  The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Main Branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://enzolita.github.io/Stronger/index.html

**Forking the Github Repository**
- You can fork a GitHub Repository to make a copy of the original repository to view or make changes without it affecting the original repository.
- Find the GitHub repository.
- At the top of the page to the right, under your account, click the Fork button.
- You will now have a copy of the repository in your GitHub account.

**Making a Local Clone**
- Find the GitHub Repository.
- Click the Code button
- Copy the link shown.
- In Gitpod, change the directory to the location you would like the cloned directory to be located.
- Type git clone, and paste the link you copied in step 3.
- Press Enter to have the local clone created.

## Credits 

#### Content

- Text content on home page and about page was generated by chatgpt and adjusted to fit the theme project.

#### Media

- Background images and videos are sourced from: https://www.pexels.com/
- Social media icons are sourced from: Font Awesome.
- Fonts (Raleway and Poppins) are sourced from: Google Fonts.

#### Code

- Inspiritaion for about us page was taken from a video by Learn Web: https://www.youtube.com/watch?v=jI-hFANig-w&t
- Inspiritaion for sign up form was taken from a video by Codehal: https://www.youtube.com/watch?v=hlwlM4a5rxg&t
- Inspiration was also taken from a Code Institute project: Love Running.

#### Acknowledgements

- The Code Institute Slack community offered valuable insight during the development of this project.
- My mentor Jubril offering and sharing his experience and feedback during the development of this project.
- Another person I would like to address in my project who has been very helpful is Harry.

