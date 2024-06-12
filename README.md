# Automatic App Landing Page
**Create and deploy an app landing page on GitHub Pages / GitLab Pages.**

Designed for super easy set up. 

🔧 Fork this repo

🗝 Update details in `_config.yml`

📲 Upload video preview or screenshot

🎨 Customise site in `_config.yml` (no HTML/CSS)

📝 Write Privacy Policy as markdown in `privacypolicy.md`

🕒 Keep a changelog in `CHANGELOG.md`

## Local Development
You need Ruby and Jekyll installed. Learn more at [LOCAL_DEVELOPMENT.md](LOCAL_DEVELOPMENT.md)

```
bundle install
bundle exec jekyll serve
```
## Quick Start

### Step 1: Fork this repo.
#### Github
After forking the repo, your site will be live immediately on your personal Github Pages account, e.g. `https://yourusername.github.io/your-repo-name/`.

*Make sure GitHub Pages is enabled for your repo. It might take some time for the site to propagate entirely.*

#### GitLab
After forking, For the first time you may need to manaully trigger the Pipeline. From the side navigation, Click in Build -> Pipelines -> Run Pipeline -> Run Pipeline

*It will take few minutes to complete the build process.*

You have to make the pages available to everyone as well. Settings -> General -> Visibility, project features, permissions -> Pages Set it to Everyone and click in Save Changes.


### Step 2: Enter about your app in `_config.yml`

These are required
page_title - title of the page
playstore_link - link of the app in playstore
app_icon - icon of the app (need to upload the image)
app_name - name of the app
app_price - price of the app

If you have If your target is ios app.
1. provide `ios_app_id` and 
2. set `auto_populate_from_ios` to true All the above fields will be populated
    1. else fill in those details above and fill in `appstore_link` as well.
3. set `device_preview_type` to ios

You can go on with customising almost anything in the `_config.yml` file. 

Things you can customise in `_config.yml`:
- App Name
- App Icon
- App Description
- App Price
- App Store Link
- Play Store Link
- Press Kit Download Link
- Cover Image
- Cover Overlay Color
- Background Color
- Text Colors
- iPhone Device Color
- Your Name / Company Name
- Link to Website
- Social Links and Contact Info
- Feature List (Title, text, icon)



### Step 3: Add screenshot or video

#### Adding a screenshot
Upload a `.png` or `.jpg` of your app to the folder `assets/screenshot/`. The name does not matter. Be sure to delete the placeholder `yourscreenshot.png`.

#### Adding video
Upload your video to the folder `assets/videos/`. To have support for most browsers, you need to upload two files – one for Safari and one for Chrome/Firefox.

Video formats supported by Chrome and Firefox:
- `.webm`
- `.ogg`

Video formats supported by Safari:
- `.mp4`
- `.mov`

#### Resolutions
The videos and screenshots must have one of the following resolutions:
- 828x1792
- 1125x2436
- 1242x2688



### Step 4: Edit (or remove) Privacy Policy and Changelog
Your site automatically includes pages for a Privacy Policy and a Changelog. Change the content of these pages by editing the `privacypolicy.md` and `CHANGELOG.md` files in the `_pages` directory.

In each of the markdown files, you can set the `include_in_header:` value to either `true` or `false`. This determines if the page is included in the top navigation.
By default, only the Changelog is included in the top navigation. The title of the navigation item can also be edited, by editing the `title:` in each markdown file.

If you need to, you can create additional markdown based pages just by creating an `.md` file like the `privacypolicy.md` and `CHANGELOG.md` files in the `_pages` directory.

**Please note:** The Privacy Policy and Changelog provided are written using dummy text, so please adapt each of them for your own app.
You can also choose not to include these pages, by simple deleting the `privacypolicy.md` and `CHANGELOG.md` files.




## Original Repo
[https://github.com/emilbaehr/automatic-app-landing-page](https://github.com/emilbaehr/automatic-app-landing-page)

While the Original one is focused towards iOS apps, This repo is focused for Android ones. 


## Feedback
If you have feedback regarding bugs or improvements, open an issue, @ me on Twitter or write me an email. You can find my contact info on my website.

I'd love to see the sites you create using this little tool.

## Credits
- [Jekyll](https://github.com/jekyll/jekyll)
- [FontAwesome](https://fontawesome.github.io/Font-Awesome/)

## Donations
[Donations are welcome](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=S8ZZT3JXJPN92&currency_code=USD&source=url)

## Author
[Emil Baehr](https://emilbaehr.com/)

## License
[MIT License](LICENSE)
