# Instructions on how to create a new event

## 1. Access
Get access to this repository by writing an email to [philipp.n.kling@gmail.com](mailto:philipp.n.kling@gmail.com) 
## 2. Cloning
[Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository to your local machine. Ideally, set up [ssh-access](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) or create a [personal access token](https://everhour.com/blog/github-personal-access-token/ if you want to use https-cloning.
## 3. Create event

Here you have two options: create an event with or without an image. The process differs slightly

### a) Event without image
1. Copy the [template for an event without image](https://github.com/philippnkling/swinginhd-hugo-content/blob/main/templates/event-without-image/YYYY-MM-DD_name.md) in the [post](https://github.com/philippnkling/swinginhd-hugo-content/tree/main/post) folder on your computer. 
2. Rename the file by replacing `YYYY-MM-DD_name.md` with the current date (e.g. if the event is a social dance on March 1, 2026, the file could be named `2026-03-01_social.md`.
3. Replace the content in the file with the information about your event (e.g. `<YOUR TITLE>` with `Social Practice Time`) and remove the categories that do not apply to your event.

### b) Event with image
**Careful, please only use images that you have rights for or which are available under a free licence**
1. Create a new folder with the name YYYY-MM-DD_name or copy one the [template folder]('https://github.com/philippnkling/swinginhd-hugo-content/tree/main/templates/event-with-image/YYYY-MM-DD_name'). 
2. Create or adapt the `index.md` file similar to the step 3 in the procedure of an event without an image.
3. Copy one of the [available images](https://github.com/philippnkling/swinginhd-hugo-content/tree/main/img) or add your own picture to the folder and reference it in the header (`image: <filename>`). Don't forget to attribute the picture in the last line. Suggestions on how to 

## 4. Push
This depends a little bit on the cloning/authentication method. If you set up ssh-access you should be able to use these 3 commands in your terminal:
- `git add post`
- `git commit -m "adding new event"`
- `git push`

The changes in the `post`folder automatically trigger a rebuild of the website. If the rebuild is successful, the new version of the website is published instead of the old one and the changes and probably your new event is visible on the website.
