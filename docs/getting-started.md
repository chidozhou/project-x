# ProjectX - Web Application

## Overview

ProjectX is a web application aimed at building a responsive and user-friendly platform. This repository is used for version control and collaboration using Git and GitHub.

## Repository Structure

The repository has been initialized on GitHub with the following structure:

- `src`: Contains the source code for the web application.
- `docs`: Includes documentation related to the project.
- `tests`: Holds testing-related files.

## Branching and Initial Development

### Branches Created

- `feature/add-homepage`: A new branch created for developing the one-page website.
- `feature/add-about-page`: Another branch created for adding an about page.

### Website Development

A one-page website has been developed within the `src` folder, including sections such as a header, about, services, and contact. Changes were committed with clear and descriptive commit messages.

## Collaboration and Pull Requests

[Tapiwanashe Mlambo](https://github.com/tapiwamla) has been invited to collaborate on the repository. The following actions were taken:

1. [Tapiwanashe Mlambo](https://github.com/tapiwamla/) created a branch named `feature/add-about-page`.
2. He changed 'About Us' to 'About The Company'
3. A review was conducted, providing suggestion for styles.

## Merging and Conflict Resolution

1. The `feature/add-about-page` branch was merged into the main branch.
2. A deliberate conflict was introduced between the main branch and the `feature/add-homepage` branch by changing 'About The Company' to 'Who We Are' on the same line, 16.
3. Conflict was resolved by going agreeing to 'About The Company' and merged successfully.

## Version Control Analysis and Problem-solving

1. A bug was intentionally introduced in the code of one of the branches: using `hl` instead of `h1` for the main tag.
2. We used `git log` to identify the commit that introduced the bug.
3. The best way was to revert to that commit hash.