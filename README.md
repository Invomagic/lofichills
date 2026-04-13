# Nebula Docs 🌌
Nebula Docs is an Open-Sourced Documentation Project ive made, it started as the internal documentation website i use for @invomagic which i've now tidied up, added a few extra classes, and then templatized in a way!
My hope is that someone finds a use for it :) its very easy to put behind Cloudflare ZT Access

## Setup 🔧
Setup is fairly easy :)

Fork this Repository, and, ideally in an IDE, such as VSC start editing the files, its very lightweight as its pure HTML & CSS
If you need another page, i'd suggest duplicating a page, so you get its base look instantly and dont need to resetup the inial HTML

You can create as many pages as you want :) Mostly you only need to know HTML and how to assign classes to tags (you put class="class name" in the tag to do so) to build your documentation

## CSS Classes 🎨

"page-title" - Large, centered primary heading.

"section-divider" - Indented sub-heading for separating content sections.

"content-text" - Standard paragraph text with a slight left margin.

"text-center" - Utility class for center-aligning text.

"navbar" - Main navigation bar with custom font and background image.

"main-content" - Flex container for centering and stacking the primary page content.

"content-body" - Large, bold text container for main body blocks.

"text-info" - Light blue text for informational messages.

"text-warning" - Orange text for warnings or alerts.

"text-danger" - Red text for errors or critical warnings.

"text-success" - Green text for success messages.

"video-container" - Responsive, centered container with a shadow for embedding 16:9 videos.

"an-image" - Responsive, centered image with rounded corners (max width 600px)

## Deploy 🚀
After Forking the Repository you can deploy it on well, pertty much anything that'll support a static site, but i'd Reccomend **Cloudflare Pages**, GitHub Pages, Vercel, or Netlify

### Cloudflare Pages 🌩️
1. Head to https://dash.cloudflare.com
2. Go over to "Compute" expand it
3. Click on "Workers & Pages"
4. Click on "Create Application"
5. Click on the 'Get Started' in the phrase you see below "Looking to deploy Pages? Get started"
6. Click "Import an existing Git repository"
7. Select (or connect) a your GitHub account, then select the repo you want to deploy
8. Click Begin Setup, then Click Save and Deploy

 ### Vercel ▲

1. Head to https://vercel.com
2. Click "Add New..." in the top right, then select "Project"
3. Under "Import Git Repository", select (or connect) your GitHub account
4. Find and click "Import" on the repository you want to deploy
5. Configure your Project Name (or leave it as the repo name)
6. Click "Deploy" and wait for it to build your site

### Netlify 🌠
1. Head to https://app.netlify.com
2. Click on "Add new site" in the top-right dropdown
3. Click "Import an existing project"
4. Choose GitHub as your Git provider
5. Authorize Netlify to access your GitHub account (if prompted)
6. Select the repo you want to deploy from the list
7. Leave the "Build command" field empty 
8. Leave the "Publish directory" field empty (or put `.` if it complains)
9. Click "Deploy site"

### GitHub Pages 🐙
1. Visit your repository page
2. Go to Repo settings
3. Under 'Code and automation' click "Pages"
4. Set source to "Deploy from a branch"
5. Set Branch to main
6. Set the thing text to it "/ (root)"
7. Click Save

## Hope you Enjoy! ✨
This is my first Open Source project, and im quite new to building websites in all honesty :p so i hope this is of use to anyone<br>
Best,<br>
~ Magic ^^
