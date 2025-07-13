# Om Kulkarni - Personal Portfolio

This repository contains the source code for my personal academic and portfolio website, built with Jekyll and hosted on GitHub Pages.

**Live Site:** [https://om-kulkarni.github.io/](https://om-kulkarni.github.io/)

## About This Site

This website showcases my projects, work experience, and academic background in robotics and software engineering. It serves as a central hub for my professional and academic work.

### Features:
*   **Projects:** A collection of my work in robotics, including projects on robot control, computer vision, and human-robot interaction.
*   **Work Experience:** A summary of my professional roles and contributions.
*   **Resume:** My up-to-date resume.
*   **Publications:** A list of my academic publications.

## Technologies Used

*   **Jekyll:** A static site generator that's perfect for personal, project, or organization sites.
*   **GitHub Pages:** Hosting directly from my GitHub repository.
*   **Markdown:** For creating and editing content.
*   **Academic Pages Template:** The Jekyll theme this site is based on.

## Setting Up Your Own Site

You can use this repository as a template to create your own academic portfolio website.

### Option 1: Use This Repository as a Template
1.  **Clone this repository:**
    ```bash
    git clone https://github.com/Om-Kulkarni/Om-Kulkarni.github.io.git your-new-website
    ```
2.  **Set up your GitHub Pages repository:** You will need to create a new repository on your GitHub account named `<your-github-username>.github.io` and push the code from this template to it.
3.  **Customize the content:**
    *   Update `_config.yml` with your personal information.
    *   Replace the files in `_projects`, `_work-experience`, `_publications`, and `_posts` with your own content.
    *   Change the author details in `_data/authors.yml`.
    *   Update the navigation in `_data/navigation.yml`.
    *   Replace images in the `/images/` directory.

### Option 2: Use the Original Academic Pages Template
For a completely fresh start, you can use the original [Academic Pages template](https://github.com/academicpages/academic-pages.github.io).

## Running Locally

To preview your changes before pushing them to GitHub, you can run the website locally.

### Method 1: Using Docker (Recommended)
This is the easiest way to get started, as it doesn't require installing Ruby or other dependencies on your system.
1.  Make sure you have [Docker](https://www.docker.com/get-started) installed.
2.  Run the following command from the root of the repository:
    ```bash
    docker compose up
    ```
The site will be built in a container and will be available at `http://localhost:4000`.

### Method 2: Manual Installation
If you prefer to install the dependencies on your machine, you'll need Ruby and Bundler.
1.  **Install dependencies:**
    ```bash
    bundle install
    ```
2.  **Serve the site:**
    ```bash
    bundle exec jekyll serve
    ```
The site will be available at `http://localhost:4000`.
