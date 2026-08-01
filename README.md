# Custom Slayone Client Resource For Everyone
This is a repository for gathering the custom resources of Slay.one client,
you can use the resources here to improve your gaming experience for free,
and I welcome who wants to contribute to this repository in any forms.

# Disclamer
All copyright here remains to the developer of Slay.one - JBS, except some works that is marked that those are provided by others.
All custom resources included in this project have been manually reviewed by us.
Should any issues arise specifically from the content of these custom resources, we take responsibility.
However, users must understand that the use of any third-party custom resources may violate the official Terms of Service or End User License Agreement of Slay.one.
As such, users assume full responsibility for any consequences resulting from the use of resources here. This project is not affiliated with or endorsed by the game's official developers or publishers. Please use at your own discretion after understanding the associated risks.

# Table of Content
1. [How to use the custom resources here?](#how-to-use-the-resources-here)
2. [List of Custom Resource URLs](#list-of-custom-resource-urls)
3. [How can I contribute to this project?](#how-can-i-contribute-to-this-project)
4. [Contacts](#contacts)
5. [Contributors](#contributors)

# How to use the resources here?
First, you will need to install a browser extension for override the original resource to custom resource.

## Steps for Chrome User
1. Visit https://chromewebstore.google.com/detail/resource-override-mv3/pfepcehfolngpmjnkclobnhejfbnbdno
2. Click "Add to Chrome" button.
3. Click "Add extension" button.
4. Click on the icon of extensions on top right.
5. Find "Resource Override" in there, and click the icon of 3-dots.
6. Click on "Options"
7. Now you can add the redirect/override rules depends on your need.
  - Example: ![Example Of Redirect Extension Configuration](https://flashxwx.github.io/custom_slayone/example_of_redirect_extension_configuration)
8. Click on "Save Changes", after adding redirect/override rules.

Find the custom resource urls you want to use in below.

# List of Custom Resource URLs

## Bug Fixs & Features
Redirect https://slay.one/dist/client-bundle.js (client codes) to
- https://flashxwx.github.io/custom_slayone/resource/main/dist/client-bundle.js
  - Made message in global chat selecable.
  - Fixed some issues that are very very small, but making the user experience smoother.
  - Easily switch accounts that you had logged in before in slay.one Settings. To delete the saved account, please select and use Ctrl+DEL. 
  - Can trigger out social UI using Ctrl+/ in game.
  - The invite link will be clean, will not be like `https://slay.one/?server=0&room=123?server=0&room=321` or longer, and still works well.
  - (For dev) Remove the anonymous function wrapping of all js resource, you can visit `__webpack_module_cache__` in console.
  - (For dev) Remove the feature that keeps making `mainUI.style.display = "none"` when in game.

## Skins

Redirect https://slay.one/imgs/tileSheet.png (pixel arts for maps) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/tileSheet-beach.png
  - Let the map has beach theme. Partially provided by ARK77.

Redirect https://slay.one/imgs/cursor.png (default cursor) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/text.cur.png (cursor for text) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/c0.png (default cursor in-game) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/c6.png (left-click cursor in game) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/crosshair.png (red rocket cursor, light) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/crosshair2.png (red rocket cursor, dark) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/cx.png (cursor for disabling of ability use) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

Redirect https://slay.one/imgs/cb.png (cursor for teleportation) to
- https://flashxwx.github.io/custom_slayone/resource/skins/imgs/cursor-teto.png
  - Teto cursor. Shared by Mazlista. Drawn by wobbuuu on twitter.

# How can I contribute to this project?

## Method 1: Suggestion & Report
Tells us your idea of how to customize Slay.one client, we can help you to make it comes true if we think it is worth our time.
And please report anything wrong of the resources here to us, we will fix it as soon as possible.

## Method 2: Sharing
Share the custom resources that you have to us, we will merge or store them well in this repo.

## Method 3: Fork The Repo
You can fork this repo and make changes if you good at using git and github.
You can initial a pull request of your forked repo, we will accept it once we find it is safe and good.

Please follow the file structure of this repo, every folder in `/resource` got different purpose.
And the structure of folders in `/resource` normally follow the official one.

Besides, please make sure there's an info.txt file in every folders in `/resource`, for specifying the essential info, you can refer to the existing ones.

Recommended Tools: Override Feature in Chrome Dev Tools, Git, Github, and Visual Studio Code.

# Contacts
For any support of this project, please contact @**flashqwq** on Discord.

Or, you can just open issue/request of this repo on github, but it might not be found in a short time.

# Contributors
- ARK77
- Flash
- Goldberg
- Mazlista