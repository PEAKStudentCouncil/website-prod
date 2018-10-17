# PEAK Student Council

Hi everyone! We're the small representative group of students in the [PEAK program](https://peak.c.u-tokyo.ac.jp/) at the University of Tokyo. This webpage will be the future home of our activities, including event reports, a students' voice blog, newsfeeds of changes to the primary student news/updates website, and eventually - signups to join the council / media requests for contact.

If you are reading this, you can probably already see it for yourself, but the current maintaners of this project are [Alexander Tangiuchi-Wiegman](https://github.com/madicetea), [Onkar Gulatti](https://github.com/onks99), and [Abhishek Gupta](https://github.com/24abhi). We are all on GitHub under the organization called ["PEAKStudentCouncil"](https://github.com/PEAKStudentCouncil).

Questions should be directed to us in the source code control by opening an [issue](https://github.com/PEAKStudentCouncil/website-prod/issues/new), but serious issues and ethics concerns should be emailed to the [current President of the Council](mailto:peakstudentcouncil@gmail.com).

## Setup your own site

This site was made from a template in [Victor Hugo](https://github.com/netlify/victor-hugo) and [Netlify CMS](https://github.com/netlify/netlify-cms), designed and developed by [Darin Dimitroff](http://www.darindimitroff.com/).

The template uses a custom fork of Tachyons and PostCSS with cssnext and cssnano (see Javascript files). To customize the template for your brand, refer to `src/css/imports/_variables.css` where most of the important global variables like colors and spacing are stored.

## Local Development

Clone this repository, and run `yarn` or `npm install` from the new folder to install all required dependencies.

Then start the development server with `yarn start` or `npm start`.

For users of the git CLI interface, the following commands are suggested to start pushing to the development branch:

1) git checkout -b development (please verify the blue text has changed from 'master' to 'development'

2) git remote -v (please verify your remote is correct)

3) git push --set-upstream origin development (when you make your first push to the live-web GitHub SVN)

## Live Development

First, use the deploy button to get your own copy of the repository:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify-templates/kaldi-hugo-cms-template)

Once that is done, you need to setup the GitHub integration for Netlify CMS.

Go to https://github.com/settings/developers and register a new application.

Then go to the "Access" tab in your new Netlify site and add a GitHub authentication provider.

Once that's done, you'll be able to enter the CMS by going to the URL of your new site and appending `/admin`

## In Closing

Thanks for checking everything out and we hope this source code will be of use to others in the future.
