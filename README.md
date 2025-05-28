# Dušan Paun Jekyll Site

This is a [Jekyll](https://jekyllrb.com/) static site project.

## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/downloads/) (version 2.7 or newer recommended)
- [Bundler](https://bundler.io/)

### Installing Ruby (if not already installed)

**macOS:**  
You can use [Homebrew](https://brew.sh/):

```sh
brew install ruby
```

**Linux (Debian/Ubuntu):**

```sh
sudo apt-get update
sudo apt-get install ruby-full build-essential zlib1g-dev
```

**Windows:**  
Download and install from [rubyinstaller.org](https://rubyinstaller.org/).

After installation, you may need to add Ruby to your system PATH.

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Install Bundler (if not already installed):**

   ```sh
   gem install bundler
   ```

3. **Install project dependencies:**

   ```sh
   bundle install
   ```

## Running Locally

Start the Jekyll development server:

```sh
bundle exec jekyll serve
```

Visit [http://localhost:4000](http://localhost:4000) in your browser to view the site.

## Building for Production

To build the static site for deployment:

```sh
bundle exec jekyll build
```

The generated site will be in the `_site/` directory.

## Deployment

This project is set up for automatic deployment to GitHub Pages using GitHub Actions.  
On every push to the `main` branch, the site will be built and deployed to the `gh-pages` branch.

---