# Project: GitHub User Scraping for Hyderabad
**Data Scraping:** Using the GitHub API, we gathered data on users in Hyderabad with over 50 followers, along with their repositories.

**Interesting Finding:** After analysis, we found that JavaScript is the most popular language among Hyderabad's top developers.

## Overview
This project collects and analyzes GitHub data for users based in Hyderabad with over 50 followers. By examining user profiles and repository attributes, we aim to uncover trends in programming language preferences, license popularity, and other factors that can guide local developers in building their GitHub presence.

## Data Collection
Using GitHub's API, we retrieved profiles of users in Hyderabad with follower counts exceeding 50. For each user, we collected up to 500 of their most recently pushed repositories, capturing essential details such as programming language, stargazers, watchers, and license type.

### Files in This Repository
- **users.csv:** Contains data on each GitHub user from Hyderabad with over 50 followers. Fields include:

  - `login`: GitHub user ID
  - `name`: Full name
  - `company`: Company name (cleaned to uppercase and leading @ symbol removed)
  - `location`: City of residence
  - `email`: Email address
  - `hireable`: Open to hiring status
  - `bio`: Short biography
  - `public_repos`: Number of public repositories
  - `followers`: Follower count
  - `following1`: Following count
  - `created_at`: Account creation date

- **repositories.csv:** Lists public repositories of each user in users.csv. Fields include:

  - `login`: GitHub user ID of repository owner
  - `full_name`: Repository name
  - `created_at`: Repository creation date
  - `stargazers_count`: Star count
  - `watchers_count`: Watcher count
  - `language`: Repository programming language
  - `has_projects`: Projects enabled status
  - `license_name`: Repository license type
- **README.md**: Documentation outlining data collection methods, insights from the analysis, and actionable recommendations for developers.

## Analysis and Findings

After analyzing the data, several key insights emerged:

1. **Programming Language Preference**: JavaScript is the most popular language among Hyderabad’s most-followed developers.
2. **License Popularity**: The most common licenses among Hyderabad developers are MIT, Apache-2.0, and others.
3. **Community Engagement**: Many prominent developers in Hyderabad actively contribute to open-source projects.

## Recommendations for Developers

Developers in Hyderabad looking to improve their GitHub presence may benefit from contributing to popular open-source projects, especially those in languages widely used by the local developer community. Engaging with such projects can increase visibility and foster connections with other professionals in the area.
