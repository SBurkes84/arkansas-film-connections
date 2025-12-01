# Arkansas Film & Actor Connections

This is my Capstone 2 web project, built to highlight films and actors with ties to the state of Arkansas.  
I used it as a way to practice planning, designing, and building a small, focused website that I can host on GitHub Pages and include in my portfolio.

## Project Overview

The site explores how Arkansas shows up in film through:

- Movies that were filmed in Arkansas  
- Actors and actresses who were born in, lived in, or are strongly connected to Arkansas  
- Stories that tie back to Arkansas locations, culture, or history  

The main goal is to organize this information in a clean, cinematic layout that feels more like a little movie experience than a plain list of links.

## Features

- **Hero section** with custom “Arkansas Film & Actor Connections” poster artwork  
- **Featured Films** section with eight example titles and short descriptions  
- **Clickable film posters** that link out to IMDb pages  
- **Actor & Arkansas Connections** section that shows how specific actors are tied to the state  
- **Clickable actor names** that open Wikipedia profiles in a new tab  
- **Animated marquee banner** with a “Now Showing” feel  
- **Gradient background, glow effects, and hover states** for a more cinematic presentation  
- **Google Analytics integration** to track page visits and basic usage

## Technologies Used

- **HTML5** for structure  
- **CSS3** for layout, gradients, glow effects, and responsive design  
- **A tiny bit of JavaScript (Google Analytics snippet)** for tracking  
- **GitHub Pages** for hosting

No frameworks were used — everything is built with plain HTML and CSS to keep the focus on fundamentals.

## Page Structure

The site has three main sections:

1. **Home / Hero**  
   - Project title  
   - Short description of the site  
   - Call-to-action buttons that jump to the Films and Actors sections  
   - A custom poster image for the project

2. **Films with Arkansas Connections**  
   - Eight featured films  
   - Each film card includes:
     - Genre badge  
     - Poster image  
     - Title and year  
     - Short description  
     - Explanation of the Arkansas connection  
     - Related tags (actor, award, location, etc.)  
   - Clicking on a poster opens the film’s IMDb page in a new tab.

3. **Actor & Arkansas Connections**  
   - List of actors and public figures tied to the featured projects  
   - Each item explains how that person connects back to Arkansas  
   - Actor names link out to their Wikipedia pages for more background

4. **About This Project**  
   - A short write-up about my process  
   - How I moved from idea → planning → layout → final design  
   - A second view of the custom poster art

## Google Analytics

Google Analytics is included in the `<head>` of the page using the standard GA4 snippet.  
To make it work with my own account, I replaced the placeholder ID (`G-XXXXXXXXXX`) with my actual Measurement ID from Google Analytics.

This lets me:

- See how many times the page is viewed  
- Confirm that other people are actually reaching the site  
- Show that I know how to add basic analytics to a static website

## Data Sources

Content for this site was created using publicly available information from:

- **Encyclopedia of Arkansas** – for lists of Arkansas-related films and actors  
- **IMDb (Internet Movie Database)** – for film years, genres, cast, and plot summaries  
- **Wikipedia** – for actor biographies and background details

I did not copy full text — I read the sources and then rewrote the descriptions in my own words and research.

## How to View the Project

If this repository is published with GitHub Pages, the site can be viewed in a browser using the GitHub Pages URL for this repo.

- https://sburkes84.github.io/arkansas-film-connections/

You can also open the `index.html` file directly in a browser to preview it locally.

## Future Improvements

If I continue working on this project, some ideas I might add are:

- Individual detail pages for each film and each actor  
- A search or filter bar to quickly find films by genre or actor  
- More titles and deeper coverage of Arkansas’s film history  
- A mobile menu toggle for very small screens

---

This project is a snapshot of my current skills in front-end web development and my ability to take a set of requirements and turn them into a finished, styled website.
