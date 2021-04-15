# Hook Grip Tech Website
![amiresponsonsive JPG](https://github.com/slammer1870/ci-ms-1/blob/main/assets/img/amiresponsive.png)
Code Institute Milestone 1 Project

## User Experience
The purpose of this website is to be a single landing page desinged to provide the user with succinct explaination of the product with features and basic configuration details, an iframe for demoing the software and a contact form within a modal for a clean user journey.

- ### User Goals
The fundamental experiences we seek to provide are:
1. Minimal ambiguitity in terms of the product, features and usage. Clear, well articulated copy that is easy to read.
2. Ease of navigation, hence the single page with the contact form in a modal to incentivise form usage without any other distractions on the page.
3. A basic demo of the product for users to familiarise themselves with the look and feel of the product.

## Design
### Colour Scheme
The colour scheme is based around off-whites and dark greys with Bootstrap's standard blue used for interactive elements like submit buttons.
### Typography
The typeface used on this site is Montserrat. Montserrat has a sharp professional feel that goes well the the brand and looks great on mobile. San Serif is used as a back up font.
### Images
The hero image is a high quality image with a CSS gradient overlay to incentivise users to scroll down.

### Wireframes
The wireframes for this project were mocked up with Adobe XD

[Mobile Wireframes](https://github.com/slammer1870/ci-ms-1/blob/main/assets/wireframes/mobile-wireframe.png)

[Desktop Wireframes](https://github.com/slammer1870/ci-ms-1/blob/main/assets/wireframes/web-wireframe.png)

## Features
Single page, fully responsive with in interacitve iframe to demo the product.

## Technologies Used
### Languages
- Html
- CSS
- Javascript

### Frameworks, Libraries & Programs Used
1. [Bootstrap 5:](https://getbootstrap.com/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Montserrat' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the VSCode plugin to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Formspree:](https://formspree.io/)
    - The Formspree API was used for handling form submissions.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.

```

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

I performed a lighthouse test using the Chrome Dev Tools. There were some best practice issues to be found as a consequence of using jQuery and some of the operation of the content within the iFrame logging errors and issues to the console. [Lighhouse Report](https://github.com/slammer1870/ci-ms-1/blob/main/assets/testing/lighthouse-report.pdf)

## References
The mobile phone graphic was built with CSS from W3Schools [Device Look](w3schools.com/howto/howto_css_devices.asp)

All Icons are from [Font Awesome:](https://fontawesome.com/)

The Hero Image is from [MaggieLeft](https://maggieleft.com/)

My Mentor, Reuben guided me along in the process of building this website.
