# Webster Kanzamba Portfolio

## Images

The portfolio photos are kept in two places: the `images/` folder and the project root. The featured gallery images use paths such as `images/photo.jpg`; the other gallery photos are loaded from the project root by the script in `index.html`. Keep the files in their current locations and preserve the exact filename spelling and letter case when adding or renaming photos. Spaces in dynamically loaded filenames are URL-encoded by the page.

Each gallery image has alternative text describing its subject. The caption beneath it names the project or type of work, and selecting a photo opens a larger view.

## Deploy to Netlify

This is a static HTML site; it has no build step or package dependencies. The included `netlify.toml` tells Netlify to publish the project root, where `index.html` and the root-level photos are located. Deploy the project folder through Netlify Drop or connect the repository in Netlify. Leave the build command empty.