# Setup
This site uses Hugo for a JAWL stack.

https://github.com/gohugoio/hugo

sudo apt-get Hugo

### Manual Hugo Menu
[menu]
  [[menu.main]]
    name = "Home"
    pre = "home"
    url = "/"
    weight = 1
  [[menu.main]]
    name = "Posts"
    pre = "pen-tool"
    url = "/posts/"
    weight = 2
  [[menu.main]]
    name = "Tags"
    pre = "tag"
    url = "/tags/"
    weight = 3

## Hugo Custom Theme Docs
https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/
https://levelup.gitconnected.com/a-quick-tutorial-on-hugo-templates-creating-your-theme-a4102b42a85f
https://gohugo.io/templates/menu-templates/#section-menu-for-lazy-bloggers

### Icons?
https://github.com/feathericons/feather#client-side-javascript

## Hugo Docs
https://gohugo.io/documentation/

Just a few more steps and you're ready to go:

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>/<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

Visit https://gohugo.io/ for quickstart guide and full documentation.

### If you get canberra error ( neither of these worked, so w/e, https://askubuntu.com/questions/208431/failed-to-load-module-canberra-gtk-module )
sudo apt-get install libcanberra-gtk-module
sudo apt-get install libcanberra-gtk-module:i386        // might need this if still error

## Hugo Theme Inspo
https://github.com/zerostaticthemes/hugo-whisper-theme      ( documentation )
https://themes.gohugo.io/themes/hugo-winston-theme/         ( general presentation )

## Didn't make the framework cut
https://demo.vercel.blog/

### Content Types
* Articles ( blog )
* Series
* Pieces
* Shader Resource Site ( this is a full resource meant to help people learn shaders and get up to speed fast, especially when it comes to things like lighting models )

#### Articles
Just listen to things people have grammed or tweeted at you. What are they asking?
- What software to you use
- How can I start?
- How do you make these?
- What is your process?
- Find more questions

#### Additional Optional Content Types
* Featured ?
    - Art
    - Sites
    - Articles
* Legacy
    - 30 Days of Shade
    - Cipher Prime
    - Stupid Desk
    - Other Stuff

### Feature Needs

* Full Site Takeover - for generative pieces
https://discourse.gohugo.io/t/what-is-a-better-way-to-include-a-full-external-html-page-and-its-resources-into-blog/9287

