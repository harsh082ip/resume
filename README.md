# Resume 

*I'm Harsh Vardhan Singh, an experienced Flutter developer on a mission to craft sleek and user-friendly mobile applications. What sets my tech journey apart is my boundless curiosity for cloud computing; I'm enthusiastic about harnessing its transformative power to create cutting-edge solutions. Based in the enchanting and diverse landscapes of India, I channel the vibrancy of my surroundings into my work, constantly pushing the boundaries of innovation. My commitment to staying at the forefront of app development and cloud technologies drives me to deliver seamless digital experiences and drive real-world impact.*

![img](images/screenshot.png)

## Docs

### Running locally

To test locally, run the following in your terminal:

1. Clone repo locally
1. `bundle install`
2. `bundle exec jekyll serve`
3. Open your browser to `localhost:4000`

### Running locally with Docker

To test locally with docker, run the following in your terminal after installing docker into your system:

1. `docker image build -t resume-template .`
2. `docker run --rm --name resume-template -v "$PWD":/home/app --network host resume-template`

### Customizing

First you'll want to fork the repo to your own account. Then clone it locally and customize, or use the GitHub web editor to customize.

#### Options/configuration

Most of the basic customization will take place in the `/_config.yml` file. Here is a list of customizations available via `/_config.yml`:


#### Editing content

Most of the content configuration will take place in the `/_layouts/resume.html` file. Simply edit the markup there accordingly

### Publishing to GitHub Pages for free

[GitHub Pages](https://pages.github.com/) will host this for free with your GitHub account. Just make sure you're using a `gh-pages` branch, and the site will automatically be available at `yourusername.github.io/resume-template` (you can rename the repo to resume for your own use if you want it to be available at `yourusername.github.io/resume`). You can also add a CNAME if you want it to be available at a custom domain...





## Contributing

If you spot a bug, or want to improve the code, or even make the dummy content better, you can do the following:

1. [Open an issue](https://github.com/jglovier/resume-template/issues/new) describing the bug or feature idea
2. Fork the project, make changes, and submit a pull request

