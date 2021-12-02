# MicroTrain2111 UI Bootstrap Layout
UI Website Designed in Bootstrap. Bootstrap is a front end component library designed to allow for rapid front end development of responsive websites.

Let's start by creating a basic minimal Bootstrap layout that loads the Bootstrap assets from a CDN. Create the path and add the following /var/www/bootstrap/index.html.

## Grid layout
Add the following to the .container div below the paragraph. View this in both full screen and in phone mode to see how various view ports change the display.
* Add a navigation bar with a logo (just your name is fine)
* Add navigation links
* Add cards in a grid
* Add a jumbotron (V4.6)

## Information from HTML/CSS Lesson
* CSS - Restyle pages with new navigation - black bar with menu drop down on all pages
* Sass - Installed SASS, Exercises and Implement in github.io
* Gulp - Installed Gulp, configure, watch and build
* CSS Based Layouts & Review Floats, Flexbox and CSS Grid. Choose and apply to your github pages site.

## Serve bootstrap From GitHub Repository

Log in to your GitHub account and click on the repositories tab 
Create the `bootstrap` Repository - NO ReadME, NO License

Open a terminal (command line or CLI) and navigate to the `bootstrap` directory.

Replace XXX with your GitHub username.

```sh
cd /var/www/bootstrap
```

```sh
git init
git add .
git commit -am 'LAB - Personal Website'
git remote add origin git@github.com:XXX/bootstrap.git
git branch -M main
git push -u origin main
```

Then navigate back to Github.com and the `bootstrap` Repository folder.
* Choose **_Settings_** in the far right corner
* Scroll down to **_GitHub Pages_**
* Under Source dropdown select **_main branch_**

**Note**
> Message will change to _Your site is ready to be published at [https://`<yourname>`.github.io/bootstrap]_

* Right click on the GItHub pages link to Navigate to your site url.