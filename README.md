This theme was designed by Xiaoying Riley at 3rd Wave Media (http://themes.3rdwavemedia.com/). Visit her website for more themes [http://themes.3rdwavemedia.com/](http://themes.3rdwavemedia.com/).  [Webjeda](http://webjeda.com) made this into a Jekyll Theme: [http://webjeda.com/online-cv/](http://webjeda.com/online-cv/).  Visit their website for more Jekyll themes and for custom website design. [Eli Holmes](https://eeholmes.github.io/) modified Webjeda's design to make it more suitable for a simple flat resume.

## Installation
* Fork the repository
* Go to settings of your repository and set Github Pages source as master.
* Your new site should be ready at https://username.github.io/simple-cv/
* If you change the name of your repository, change the baseurl in `_config.yml`

## Enter your data
* Edit `_config.yml` with your name, education and summary.  The summary will appear in About Me.
* Edit `_data\experiences.yml` with your work experience.
* Edit `_data\coursework.yml` with your coursework.
* Edit `_data\skills.yml` with your skills.
* Add your picture to `assets\images\` and put the file name in `_config.yml` in `pic:`

## Customizing
* Edit `index.html` and remove sections you want.  For example, you can remove the coursework section.
* If you want to change the headers (like Work Experience), edit the corresponding file in `_includes\*.html`.
* Want a section (like Coursework) to look different? edit the corresponding file in `_includes\*.html`.
* Want a new section using an existing one as a template? Copy the existing file in `_includes\*.html` and give it a new name. Make a corresponding yml file in `_data\`.  You can copy an existing one to use as a template.  Then add an `include` to `index.html`.
* Want a new page that you can link to? Create an html file at the base level. `foo.html`.  You can use `index.html` as a template. Your new page url will be `baseurl\foo.html`.
* If you want a different favicon, delete the current one `favicon.ico` and upload a new one.

## More customizing
If you want to make css changes, then edit the css file.
* Make a copy of `assets\css\style-kz.css` and name it something else.
* Edit your copy.
* Change the `style:` line in `_config.yml` to be your new style file.
* Look at the other style files in `assets\css\` for ideas however note that `style-kz.css` has been changed from the original.  New classes: skills-section, skill-title, item in skills-section.  project-title changed to be bold.

You can find more themes at [**Jekyll Themes**](http://jekyll-themes.com)

## Reuse statement

Reuse and adapt as you wish. No attribution needed or expected.
