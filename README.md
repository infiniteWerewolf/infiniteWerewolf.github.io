# infiniteWerewolf.github.io

The Wonderful World of Wolfgang

This is a Jekyll-based website hosted on GitHub Pages. Follow the instructions below to set up your local development environment, run the site locally, and push changes to GitHub.

## Prerequisites

Before you begin, make sure you have the following software installed:

1. [Ruby](https://www.ruby-lang.org/en/downloads/) (version 2.7 or higher)
2. [Bundler](https://bundler.io/)

## Setting Up Your Local Environment

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/infiniteWerewolf/infiniteWerewolf.github.io.git
   cd infiniteWerewolf.github.io
   ```

2. **Install Dependencies:**
   - Use Bundler to install the required dependencies:
     ```sh
     bundle install
     ```

## Running the Jekyll Server Locally

1. **Start the Jekyll Server:**

   - Run the following command to start the Jekyll server:
     ```sh
     bundle exec jekyll serve
     ```

2. **View the Site:**

   - Open your web browser and go to `http://localhost:4000` to see your site. Any changes you make to the files will automatically refresh in the browser.

## Making Changes

1. **Editing Content:**

   - To add a new blog post, create a new file in the `_posts` directory. Make sure the file name follows the format `YYYY-MM-DD-title.md`.
   - To create a new page, add a new `.html` or `.md` file in the root directory or in the `_pages` directory (if it exists).

2. **Customising the Site:**
   - You can customise the look and feel of the site by editing the `_config.yml` file and the CSS files in the `assets` directory.

## Pushing Changes to GitHub

1. **Add and Commit Changes:**

   - After making changes, add and commit them:
     ```sh
     git add .
     git commit -m "Describe your changes"
     ```

2. **Push Changes:**
   - Push your changes to GitHub:
     ```sh
     git push origin main
     ```

## Troubleshooting

- If you encounter any issues, refer to the [Jekyll documentation](https://jekyllrb.com/docs/) for help.
- For any permission-related errors, ensure that you have the necessary permissions to read and write to the project directory.
