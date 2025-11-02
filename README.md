# Instructions on how to create a new event

## 1. Access

Get access to this repository by writing an email to [philipp.n.kling@gmail.com](mailto:philipp.n.kling@gmail.com) or request access via the functionality of this website.

## 2. Cloning

[Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository to your local machine. Ideally, set up [ssh-access](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) or create a [personal access token](https://everhour.com/blog/github-personal-access-token/) if you want to use https-cloning.

## 3. Create event

1. Copy the [template for an event](https://github.com/philippnkling/swinginhd-hugo-content/blob/main/YYYY-MM-DD_name.md) `YYYY-MM-DD_name.md` in the `post`-folder on your computer. 
2. Rename the file by replacing `YYYY-MM-DD_name.md` with the current date (e.g. if the event is a social dance on March 1, 2026, the file could be named `2026-03-01_social.md`).
3. Replace the content in the file with the information about your event (e.g. `<YOUR TITLE>` with `Social Practice Time`) and remove the categories that do not apply to your event.
4. Optional: if you want to add an image to your event, you can use one of the [available images](https://github.com/philippnkling/swinginhd-hugo-content/tree/main/img). In the header insert e.g. `image: social01.jpg` if you want to use the [social01.jpg](https://github.com/philippnkling/swinginhd-hugo-content/blob/main/img/social01.jpg) picture. 

*You can also add other images to the [img](https://github.com/philippnkling/swinginhd-hugo-content/tree/main/img)-folder, but please also provide a syntax to credit this picture in the [credit.csv](https://github.com/philippnkling/swinginhd-hugo-content/blob/main/img/credit.csv) (credits get automatically inserted to posts once they are referenced in this file).*

## 4. Push

This depends a little bit on the cloning/authentication method. If you set up ssh-access you should be able to use these 3 commands in your terminal:

- `git add post`
- `git commit -m "adding new event"`
- `git push`

The changes in the `post`-folder automatically trigger a rebuild of the website. If the rebuild is successful, the new version of the website is published instead of the old one and the changes and probably your new event is visible on the website.
