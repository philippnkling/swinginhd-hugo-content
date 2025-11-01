# Instructions on how to create a new event

## 1. Access
Get access to this repository by writing an email to [philipp.n.kling@gmail.com](mailto:philipp.n.kling@gmail.com) 
## 2. Cloning
Clone the repository to your local machine
## 3. Create event
Create a new folder with the name YYYY-MM-DD_<title> or copy one of the existing folders if your event matches a previous event
## 4. Insert content
Create or adapt the `index.md` file in the folder and maybe add your own picture and reference it in the header. Don't forget to attribute the picture in the last line.

Template for a new `index.md`
> title: <YOUR TITLE>
> description: <YOUR DESCRIPTION>
> date: <YYYY-MM-DD>
> image: <IMAGE-NAME.png/jpg>
> categories:
>     - Social Dancing
>     - Live Music
>     - Dance class
> tags:
>     - Private
>     - commercial
>     - costume
>     - ...
> ---
> - Address:
> - Cost:
> - Time:
>   * Start:
>   * End:
## 5. Push
- `git add post`
- `git commit -m "adding new event"`
- `git push`
