# Django-Poll-App

Django poll app is a full-featured polling app. You have to register in this app to show the polls
and to vote. If you already voted, you can not vote again. Only the owner of a poll can add poll,
edit poll, update poll, delete poll, add choices, update choices, delete choices and end a poll. If
a poll is ended, it can not be voted anymore. Ended poll only shows user the final result of the
poll. There is a search option for polls. Also, users can filter polls by name, publish date, and by
number of votes.
Pagination will work even after applying filter.

## Getting Started locally

Currently targets Python 3.9 and Django 3.1, but it is meant to change in the future.
It's a standard django application with poetry for dependency management. So:

```
git clone https://github.com/deronnax/Django-poll-app.git
poetry install
poetry run python manage.py migrate
poetry run python manage.py runserver
```

You're set. Go visit http://127.0.0.1:8000 in your browser


## Project snapshot
### Home page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409444-0e40a600-1b8c-11e9-9ab0-27d759db8973.jpg" width="100%"</img> 
</div>

### Login Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409509-36c8a000-1b8c-11e9-845a-65b49262aa53.png" width="100%"</img> 
</div>

### Registration Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409562-5cee4000-1b8c-11e9-82f6-1aa2df159528.png" width="100%"</img> 
</div>

### Poll List Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409728-d423d400-1b8c-11e9-8903-4c08ba64512e.png" width="100%"</img> 
</div>

### Poll Add Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409796-fe759180-1b8c-11e9-941b-c1202956cca4.png" width="100%"</img> 
</div>

### Polling page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409843-1e0cba00-1b8d-11e9-9109-cceb79a6a623.png" width="100%"</img> 
</div>

### Poll Result Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51409932-60ce9200-1b8d-11e9-9c83-c59ba498ca8b.png" width="100%"</img> 
</div>

### Poll Edit Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51410008-92dff400-1b8d-11e9-8172-c228e4b60e28.png" width="100%"</img> 
</div>

### Choice Update Delete Page
<div align="center">
    <img src="https://user-images.githubusercontent.com/19981097/51410442-dc7d0e80-1b8e-11e9-8f8e-18e6d7bb70fb.png" width="100%"</img> 
</div>

## Original author
Mahmudul alam Email: expelmahmud@gmail.com

