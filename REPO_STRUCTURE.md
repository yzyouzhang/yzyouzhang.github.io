# Repository Structure Documentation

This document provides a comprehensive overview of all files and directories in the yzyouzhang.github.io repository.

## Overview

This is a personal academic website for You (Neil) Zhang, built using Jekyll static site generator. The site showcases research, publications, teaching, and professional experiences.

## Root Files

### Configuration Files
- **_config.yml** - Main Jekyll configuration file containing site metadata, owner information, social media links, and Jekyll settings
- **Gemfile** - Ruby dependencies specification (Jekyll, plugins)
- **Gemfile.lock** - Locked versions of Ruby dependencies
- **.gitignore** - Git ignore patterns
- **.gitmodules** - Git submodules configuration
- **Gruntfile.js** - Grunt task runner configuration for JavaScript/CSS processing

### Documentation
- **README.md** - Repository introduction and getting started guide
- **LICENSE** - License file
- **CNAME** - Custom domain configuration

### Error Pages
- **404.md** - Custom 404 error page

### CV Files (8 versions)
- You_Neil_Zhang_CV_2024_Apr.pdf
- You_Neil_Zhang_CV_2024_May.pdf
- You_Neil_Zhang_CV_2024_Jun.pdf
- You_Neil_Zhang_CV_2024_Aug.pdf
- You_Neil_Zhang_CV_2024_Oct.pdf
- You_Neil_Zhang_CV_2024_Dec.pdf
- You_Neil_Zhang_CV_2025_Jan.pdf
- You_Neil_Zhang_CV_2025_Jul.pdf (most recent)

### Main Content Pages
- **index.md** - Homepage with bio, news, and selected publications
- **research.md** - Publications and research work
- **teaching.md** - Teaching experience and materials
- **experiences.md** - Professional experiences
- **miscellaneous.md** - Additional content
- **posts.md** - Blog posts index
- **presentations.md** - Presentations index
- **form.md** - Form page

### Site Assets
- **favicon.png** - Site favicon

## Directory Structure

### _data/
Jekyll data files for site configuration
- **navigation.yml** - Site navigation menu structure

### _includes/
Reusable HTML components
- **_author-bio.html** - Author biography sidebar
- **_browser-upgrade.html** - Browser compatibility warning
- **_cvhead.html** - CV page head section
- **_disqus_comments.html** - Disqus commenting integration
- **_feed-footer.html** - RSS feed footer
- **_footer.html** - Site footer
- **_head.html** - HTML head section with meta tags
- **_navigation.html** - Navigation menu component
- **_open-graph.html** - Open Graph meta tags
- **_scripts.html** - JavaScript includes
- **_social-share.html** - Social media sharing buttons
- **_toc.html** - Table of contents component

### _layouts/
Jekyll page templates
- **home.html** - Homepage layout
- **page.html** - Standard page layout
- **post.html** - Blog post layout
- **post-index.html** - Blog posts index layout
- **presentation-post-index.html** - Presentations index layout
- **resume.html** - CV/Resume layout
- **slide.html** - Presentation slide layout
- **form.html** - Form page layout

### _posts/
Blog posts and presentations
- **_example-presentation.md** - Example presentation file

### _sass/
SCSS stylesheets
- **coderay.scss** - Code syntax highlighting styles
- **elements.scss** - HTML element styles
- **forms.scss** - Form styles
- **grid.scss** - Grid layout system
- **mixins.scss** - SCSS mixins
- **normalize.scss** - CSS normalization
- **page.scss** - Page-specific styles
- **print.scss** - Print media styles
- **pygments.scss** - Pygments syntax highlighting
- **resume.scss** - Resume/CV styles
- **site.scss** - Main site styles
- **typography.scss** - Typography definitions
- **variables.scss** - SCSS variables (colors, fonts, etc.)

#### _sass/vendor/
Third-party SCSS libraries
- **font-awesome/** - Font Awesome icon font styles (12 files)
- **google/** - Google Fonts integration (1 file)
- **magnific-popup/** - Lightbox popup styles (2 files)

### assets/
Static assets (CSS, JavaScript, fonts)

#### assets/css/
Compiled CSS and additional stylesheets
- **main.scss** - Main stylesheet entry point
- **cvmain.scss** - CV-specific styles
- **academicons/** - Academic icons font (6 files: CSS, fonts)

#### assets/fonts/
Web fonts
- FontAwesome.otf
- fontawesome-webfont.eot
- fontawesome-webfont.svg
- fontawesome-webfont.ttf
- fontawesome-webfont.woff
- fontawesome-webfont.woff2

#### assets/js/
JavaScript files
- **_main.js** - Main JavaScript code
- **scripts.min.js** - Minified JavaScript bundle
- **plugins/** - jQuery plugins (2 files: fitvids, magnific-popup)
- **vendor/** - Third-party libraries (4 files: jQuery, html5shiv, modernizr, respond)

### images/
Image files
- **Neil_profile_photo_square.jpg** - Profile photo
- **You (Neil) Zhang_square.png** - Alternative profile image
- **2231667367623_.pic_hd.jpg** - Additional photo
- **bio-photo.jpg** - Biography photo
- **air.png** - AIR Lab logo
- **bytedance.png** - ByteDance logo
- **momenta.jpg** - Momenta logo
- **tencentAI.png** - Tencent AI logo
- **tencentmedia.jpeg** - Tencent Media logo
- **.DS_Store** - macOS system file

### contents/
Additional content files
- **GuestLec_Neil_ECE477_Fall2021.pdf** - Guest lecture slides

### resources/
Academic resources and documents
- **ICASSP2023_Rising_Star_Neil_final.pdf** - ICASSP Rising Star poster
- **Improving_Generalization_Ability_for_Audio_Deepfake_Detection_20231228_Nanjing_University.pdf** - Presentation slides
- **Personalizing_Spatial_Audio_Machine_Learning_for_Personalized_Head-Related_Transfer_Functions_(HRTFs)_Modeling_in_Gaming.pdf** - Tutorial slides
- **Teaching_Award_application_materials_Neil.pdf** - Teaching award materials
- **You_Neil_Zhang_diversity_statement.pdf** - Diversity statement
- **You_Neil_Zhang_research_statement.pdf** - Research statement
- **You_Neil_Zhang_teaching_statement.pdf** - Teaching statement

### reveal.js/
Third-party presentation framework (submodule)
- Complete reveal.js library for creating HTML presentations
- Includes plugins, themes, CSS, JavaScript, and documentation
- Maintained separately as a git submodule

## Technology Stack

### Build System
- **Jekyll 3.9** - Static site generator
- **Ruby** - Programming language for Jekyll
- **Grunt** - JavaScript task runner for asset processing

### Jekyll Plugins
- jekyll-sitemap - XML sitemap generation
- jekyll-seo-tag - SEO meta tags
- jekyll-gist - GitHub Gist embedding
- octopress - Blogging framework extensions

### Front-end Libraries
- **jQuery 1.9.1** - JavaScript library
- **Font Awesome** - Icon font
- **Academicons** - Academic icon font
- **Magnific Popup** - Lightbox plugin
- **FitVids** - Responsive video embedding
- **Modernizr** - Feature detection
- **html5shiv** - HTML5 compatibility for older browsers

### Styling
- **Sass/SCSS** - CSS preprocessor
- **Normalize.css** - CSS reset
- **Kramdown** - Markdown parser
- **Rouge** - Syntax highlighter

## File Statistics

- **Total files** (excluding .git and .sass-cache): 119
- **Content pages**: 8 markdown files
- **Layouts**: 8 HTML templates
- **Includes**: 12 HTML partials
- **SCSS files**: 26 stylesheets
- **JavaScript files**: 9 files
- **PDF documents**: 15 files (8 CVs + 7 resources)
- **Images**: 9 image files
- **Font files**: 10 font files

## Site Features

1. **Responsive Design** - Mobile-friendly layout
2. **Academic Profile** - Publications, research, teaching
3. **Social Integration** - Links to GitHub, LinkedIn, Google Scholar, etc.
4. **SEO Optimized** - Meta tags, sitemap, Open Graph
5. **Presentation Support** - Integration with reveal.js
6. **Syntax Highlighting** - Code blocks with Pygments/Rouge
7. **Icon Support** - Font Awesome and Academicons
8. **Custom Forms** - Interactive configuration forms

## Configuration Highlights

### Site Information
- **Title**: You (Neil) Zhang - University of Rochester
- **Author**: You (Neil) Zhang 张优
- **Bio**: An Audio Machine Learning Researcher @ University of Rochester
- **Email**: you.zhang@rochester.edu
- **Theme Colors**: 
  - Highlight: #FFC70A (UR gold)
  - Lowlight: #073661 (UR navy)

### Social Media Presence
- GitHub: yzyouzhang
- LinkedIn: you-neil-zhang
- Google Scholar: nYtHcRAAAAAJ
- ORCID: 0000-0002-4649-278X
- ResearchGate: You-Zhang-16

## Development Workflow

1. Edit content in Markdown files (index.md, research.md, etc.)
2. Modify styles in _sass/ directory
3. Run `bundle exec jekyll serve` for local development
4. Use Grunt for JavaScript/CSS minification: `grunt`
5. Push to GitHub - automatically built and deployed via GitHub Pages

## Notes

- The site uses Jekyll Academic template (based on Minimal Mistakes theme)
- reveal.js is included as a git submodule for presentation functionality
- Multiple CV versions are maintained with date-stamped filenames
- Site is hosted on GitHub Pages at yzyouzhang.github.io
