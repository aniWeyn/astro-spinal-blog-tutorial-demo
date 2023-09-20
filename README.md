# Spinal CMS with Astro as a Static Site Generator
## Spinal CMS
Spinal CMS has permission to read and write markdown files in this repository. Spinal CMS doesn't depend on Astro framework and this framework can be changed to other one anytime. 

[Spinal CMS](spinalcms.com/).

## Astro - Static Site Generator
This project is based on the template from [Astro Tutorial](https://docs.astro.build/en/tutorial/0-introduction/).

Astro is Static Site Generator like Gridsome or Gatsby. It has very simple source structure and is similar to other frameworks so it makes it almost instant to undesrtand.

## How to access Spinal CMS
Ask about invitation link if you would like to use your personal account.
In other cases you can just use developer email which has Administrator rights.

Spinal CMS is a third-party solution therefore you cannot access it from localhost but you can influence its' options from the code.

To login to Spinal CMS go to [Spinal CMS](https://app.spinalcms.com/login).

## Static Site Generator
### Running the project
***
Optional, but recommended steps:
- Install Visual Studio Code or other tool for front-end development [Visual Studio Code](https://code.visualstudio.com/Download)
- Login to Visual Studio Code with your GitHub account if you would like to use build in Source Control 
- Instal Astro extension for syntax & semantic highlighting, IntelliSense completions and other support
- Open cloned project with Visual Studio Code, option "Open Folder..."
*** 

1. Clone repository to Projects folder (you don't need to create a new folder)
2. Open Terminal
3. On first use run `npm install`
4. To start project use `npm run dev` 

### Editing
#### Posts/Articles
The content that is accessed by Spinal CMS lays in `src/pages/posts`. Do not delete the content of that folder.    

The posts are saved as Markdown files. Use regular [Markdown](https://www.markdownguide.org/basic-syntax/#code) for edits.   

On the top of every Markdown file there are metadata in [YAML](https://yaml.org/) format (human-friendly data serialization language for all programming languages).

#### Tags/Authors etc
Tags, authors or other data are created based on Metadata from the Posts.

#### Styling 
Global styles are laying in `src/styles/global.css`

#### Layouts
The Posts are using layouts from  `src/layouts/MarkdownPostLayout.astro` where Markdown is rendered in `<slot />` and metadata in HTML through `frontmatter`. 

#### Components
Footer or Theme icon is placed in `src/components`. Components can be imported to Layouts or Pages.

### Deploying the project
TBA

`npm run deploy` 
