### lyfeHacker - A Beautiful Author Website for Infozy's Authors

[![Travis CI](https://travis-ci.com/tks18/developr-infozy.svg?branch=develop)](https://shan.infozy.tk)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

### [Installation Guide](https://devlopr.netlify.app/get-started)

lyfeHacker uses Markdown Files to create data like Blog Posts, Gallery, Shop Products etc. No external database is required.

You can easily manage the site using the admin : [http://localhost:4000/admin](http://localhost:4000/admin)

### Deploy your devlopr-jekyll blog - One Click Deploy

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/tks18/developr-infozy)
[![Deploy with Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/tks18/developr-infozy)
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/tks18/developr-infozy)

### Website (Hosted Apps)

- Travis-CI - [here](https://shan.infozy.tk/)

#### Features :

- CMS Admin Support using [Jekyll Admin](https://jekyll.github.io/jekyll-admin/)
- Supports Latest [Jekyll 4.x](https://jekyllrb.com) and [Bundler](https://bundler.io)
- Stylesheet built using Sass
- Comments using [Hyvor](https://talk.hyvor.com/) and [Disqus](https://disqus.com/)
- Google SEO and Analytics Optimized
- Real Time Search using [Algolia](https://algolia.com/)
- Sell Stuff (Ecommerce) in your Blog using [Snipcart](https://snipcart.com/)
- Send Newsletters using [Mailchimp](https://mailchimp.com/)
- Contact Forms using [Formspree](https://formspree.io/)
- Coding Activity using [Wakatime](https://wakatime.com/)
- Hosting Support for [Github Pages](https://pages.github.com), [Netlify](https://netlify.com), [Zeit](https://zeit.co), [Heroku](https://heroku.com), [AWS Amplify](aws.amplify.com)

## Release Changes :

You can check out the latest changes [here](https://www.buymeacoffee.com/shantk18)

## Using Docker :

Building the Image :

`docker build -t my-devlopr-jekyll-blog .`

Running the container :

`docker run -d -p 4000:4000 -it --volume="$PWD:/srv/jekyll" --name "my_blog" my-devlopr-jekyll-blog:latest jekyll serve --watch`

## Using Docker Compose :

### Development :

You can run the app in development mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-dev.yml up --build --remove-orphans`

### Production :

You can run the app in production mode : (your changes will be reflected --watch moded)

Serve the site at http://localhost:4000 :

`docker-compose -f docker-compose-prod.yml up --build --remove-orphans`

Stop the app :
`docker-compose -f docker-compose-prod.yml down`
Once everything is good and ready to go live -

`docker-compose -f docker-compose-prod.yml up --build --detach`

## Contributors:

This project exists thanks to all the people who contribute.

Contributions are more than just welcome. Fork this repo and create a new branch, then submit a pull request

- 1.Fork it [http://github.com/tks18/developr-infozy/fork](http://github.com/tks18/developr-infozy/fork )

- 2.Commit your changes
`git commit -am 'Add some feature'`

- 3.Push to the branch
`git push origin my-new-feature`

- 4.Create new Pull Request

### If you like the project. Don't forget to :star: !

### For Help :

You can contact me, if you need any help via [Email](mailto:tksudharshan@gmail.com)

### Backers

Thank you to all our backers! 🙏 [Become a backer](https://https://buymeacoff.ee/shantk18)

## Licence

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT). You can do anything you want, including projects for your clients, as long as you mention an attribution back (credit links in footer). See the [Licence](https://github.com/tks18/developr-infozy/blob/master/LICENSE) file

I understand that sometimes footer links or any links to external websites are not convenient, so you have the option to remove credits/footer links by becoming a Backer.