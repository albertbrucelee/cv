[![Gem Version](https://badge.fury.io/rb/modern-resume-theme.svg)](https://badge.fury.io/rb/modern-resume-theme) [![Build Status](https://travis-ci.org/sproogen/modern-resume-theme.svg?branch=master)](https://travis-ci.org/sproogen/modern-resume-theme)
<a href="https://jekyll-themes.com">
<img src="https://img.shields.io/badge/featured%20on-JT-red.svg" height="20" alt="Jekyll Themes Shield" >
</a>



# Albert Alfrianta CV
A source for Albert Alfrianta Online CV. Open this [link](https://albertbrucelee.github.io/cv/) to view the online CV.


## Development

### Locally

Before you start make sure you have *Ruby* and the gems for *Jekyll* installed locally. You can find out how to do that [here](https://jekyllrb.com/docs/installation/).

*Note: You will need version `1.15.2` of bundler, as this is the only version that Heroku supports.*

1. Fork and or clone this repository locally
2. `cd cv`
3. `bundle install`
4. `bundle exec jekyll serve`
5. Open your browser to `http://localhost:4000`

Any changes you make will automatically build and you will be able to see these by refreshing your browser. To find out more about *Jekyll* take a look [here](https://jekyllrb.com/docs/usage/).

*Note: You will need to re-run `bundle exec jekyll serve` to see changes made in `_config.yml`.*

### Docker

If you have docker installed you can simply run `docker-compose up` to launch the site in a container, it will then be hosted at `http://localhost:4000`

## Credits

- This Online CV is created from: [sharu725/online-cv](https://github.com/sharu725/online-cv).
- [Development](#development) instruction is copied from [sproogen/modern-resume-theme](https://github.com/sproogen/modern-resume-theme).

## License

This project is licensed under the [MIT license](LICENSE.txt).
