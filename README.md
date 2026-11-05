# Complete Placement & Resource Hub 2026

An interactive, single-page placement preparation hub that brings together placement roadmaps, DSA learning paths, coding practice links, interview preparation material, YouTube learning resources, and study notes in one searchable interface.

The page is built with **HTML, CSS, and vanilla JavaScript**. It requires no framework, backend, package installation, or build process.

## Features

- **Placement preparation roadmap** covering company types, preparation timelines, programming languages, computer science fundamentals, projects, aptitude, resumes, interviews, and company-specific preparation.
- **DSA roadmap and practice resources** covering programming fundamentals, data structures, algorithms, problem-solving patterns, and a collection of 200 clickable coding-problem links.
- **A-to-Z placement kit** with resources for technical skills, courses, soft skills, developer tools, projects, certifications, portfolios, resumes, and job searching.
- **Learning resources** with topic-based YouTube shortcuts, study notes, Google Drive folders, GitHub repositories, and startup directories.
- **Category navigation** to switch between All Resources, Placement Roadmap, DSA Roadmap, A-to-Z Placement Kit, YouTube Playlists, and Study Notes / Drive / Startups.
- **Live search** to filter topics and resources by keywords such as a DSA problem, company, technology, playlist topic, or resource name.
- **Expandable topic cards** so each roadmap stays compact until you open the topics you need.
- **Expand All / Collapse All** controls for quickly opening or closing the visible topic cards.
- **Reading progress indicator** at the top of the page that follows the browser's scroll position.
- **Responsive layout** designed to work on desktop and smaller screens.
- **Direct external links** that open resources in a new browser tab.

## Resource Categories

| Category | Includes |
|---|---|
| Placement Roadmap | Placement process, timelines, programming languages, CS fundamentals, projects, aptitude, resumes, and interview preparation |
| DSA Roadmap | Programming fundamentals, arrays, strings, linked lists, stacks, queues, hashing, trees, graphs, sorting, searching, dynamic programming, and more |
| DSA Coding Questions | Clickable problem links grouped by topic, including arrays, linked lists, stacks, trees, graphs, hashing, dynamic programming, strings, bit manipulation, and advanced data structures |
| A-to-Z Placement Kit | Core skills, courses, communication, productivity tools, projects, certifications, portfolios, application materials, and job search resources |
| YouTube Learning Resources | Topic-based video learning shortcuts across AI, machine learning, programming, cloud, data, and other technical areas |
| Study Notes & Other Resources | Google Drive study folders, GitHub repositories, startup directories, and career tools |

## Getting Started

### Run locally

1. Download or clone this repository.
2. Open the HTML file in a modern web browser.
3. Start browsing the categories, searching for topics, and opening the resource links.

No local server is required for normal use. The page runs directly in the browser.

### Recommended repository layout

For a GitHub Pages site, keep the HTML page in the repository root and name it `index.html`:

```text
placement-resource-hub/
├── index.html
└── README.md
```

If your downloaded HTML file has a different name, either open that file directly or rename it to `index.html` before publishing with GitHub Pages.

## Publish with GitHub Pages

1. Push `index.html` and `README.md` to the root of your GitHub repository.
2. Open the repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your deployment branch (commonly `main`) and the `/ (root)` folder.
5. Save the settings and wait for GitHub Pages to publish the site.
6. Open the published URL shown in the Pages settings.

GitHub may take a short time to publish the first deployment. Subsequent commits to the selected branch will update the site.

## Technology Stack

- **HTML5** — page structure and resource content
- **CSS3** — dark theme, responsive grids, cards, animations, and visual styling
- **Vanilla JavaScript** — roadmap rendering, category filtering, search, expandable cards, and scroll progress
- **Google Fonts** — Space Mono and Syne, loaded from Google Fonts

## How the Interactions Work

- Select a category tab to show the corresponding resource group.
- Enter a keyword in the search field to filter the topics in the selected category.
- Select a topic card to reveal its related links and notes.
- Use **Expand All** or **Collapse All** to control all currently visible cards.
- Scroll through the page to see the reading progress indicator update.
- Select a highlighted resource link to open its destination in a new tab.

**Note:** The progress indicator reflects page scroll position. It does not save completed topics or track an individual user's placement-preparation progress.

## External Resources & Attribution

This hub brings together links to external learning and career resources. The source shortcuts include resources from [Let's Code](https://www.lets-code.co.in/), alongside platforms such as LeetCode, YouTube, Google Drive, GitHub, and other educational websites.

Some video shortcuts open a YouTube search-results page for the relevant topic rather than a single fixed playlist. External links, availability, and access permissions are controlled by their respective providers and may change over time.

Please refer to the original websites for the latest content and terms of use. The owners of linked material retain their respective rights.

## Project Notes

- This is a **static front-end project**. It does not require a database, API server, or user account.
- An internet connection is needed to load the Google Fonts and access external resources.
- The resource collection is provided for learning and placement-preparation convenience. Review the linked material and choose resources that match your own preparation plan.

---

**Built to make placement preparation resources easier to find, explore, and use.**
