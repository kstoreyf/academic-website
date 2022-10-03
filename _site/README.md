# KSF's Academic Website

This is my website! 
You can find it on the web at [https://cosmo.nyu.edu/ksf/](https://cosmo.nyu.edu/ksf/).
It uses the Alpha theme from [HTML5 UP](https://html5up.net/), converted to jekyll by [Andrew Banchich](https://github.com/andrewbanchich/alpha-jekyll-theme), and edited for style by me.

The following are reminders for myself:

### How to update

- First, make sure you have the proper gems installed. If the below commands don't work, check out the [jekyll instructions](https://jekyllrb.com/docs/).
- Make edits in local git repo.
- From repo directory, run `bundle exec jekyll serve`. Navigate to [http://localhost:4000/ksf/](http://localhost:4000/ksf/) to preview (don't forget the final backslash!).
- When done with edits, run `bundle exec jekyll build`. (If the CSS doesn't render, you likely forgot this step!)
- Push changes to git, and pull into repo on remote server where website is hosted. Copy the contents of the `_site` directory into the public website directory (`cp -r academic-website/_site/* public_html`).  
- Navigate to your newly updated website at [https://cosmo.nyu.edu/ksf/](https://cosmo.nyu.edu/ksf/)!


### Other notes

- Make sure to add updates to both \_includes/updates.md and page\_updates.md. (TODO: make it automatically pull recent updates from full page!)
- Add files and pdfs for public distribution directly to the respective directories in public\_html on the remote server.
