# NCAI-2020

A site built for a conference. This site is built using [jekyll](https://jekyllrb.com) and runs on [netlify](https://netlify.com).

## Getting Started

### Prerequisites

1. Make sure `ruby` and `gem` is installed. \
   `ruby -v` \
   `gem -v` \
   If not, make sure to install it.
2. Install `bundle`, `bundler` and `jekyll`. \
   `sudo gem install bundle jekyll bundler`

### Runing The Site Locally

1. Clone the site first. \
   `git clone https://github.com/ajaidanial/NCAI_2020.git`
2. Change to the project root. \
   `cd NCAI_2020`
3. Install the necessary gems required by the site. \
   `bundle install`
4. Run the local development server. \
   `bundle exec jekyll serve`
5. Visit the development server address in your favourite browser. By default it is `localhost:4000`.

## Contributing To This Project

### Prerequisites

Would recommend the following to be installed and used for proper code maintainability.

1. `Visual Studio Code` or called as `VSCode` - Text Editor
2. `Editorconfig` and `Beautify` - VSCode Extensions
3. Make sure that `Editor: Format On Save` is checked on `VSCode Settings`

### Development

1. Clone the site first. \
   `git clone https://github.com/ajaidanial/NCAI_2020.git`
2. Make sure to create a new branch. \
   `git checkout -b <branch_name>`
3. Make all your desired changes.
4. Commit and push all your changes. \
   `git add .` \
   `git commit -m "<commit_message>"` \
   `git push origin <branch_name>`
5. Create a `Merge Request` or `Pull Request` from your `branch_name` to the `master` branch from your account.

## Project Structure

The site follows the normal site structure as mentioned in the jekyll documentation [here](https://jekyllrb.com/docs/structure/).

### File and Folder Descriptions

The project root or the folder where you find the `Gemfile` is called as `Project Root` or `/`.

`/readme.md` => contains the project documentation.

`/Gemfile` => contains the project dependencies.

`/*.html` => the basic html pages.

`/beautifyrc.json` => contains the config for `Beautify` code formatter.

`/.gitignore` => contains files to be ignored by `git`.

`/.editorconfig` => contains config for `Editorconfig` text editor configurations.

`/_config.yml` => site global data and config for jekyll.

`/assets/` => contains css, js and other assets for the site.

`/_layouts/` => the layouts for the site, that are used in the html pages.

`/_includes/` => the common portions of the site that are used in multiple html pages.

`/_data/` => the data for the site, used in the html pages.
