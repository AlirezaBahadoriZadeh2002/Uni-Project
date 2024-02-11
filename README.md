# Uni-Project
#### The final project of the undergraduate degree of the university
<hr>

![](web-page.jpg)

## How to run Locally?

### Setting up python environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Installing dependencies

```bash
pip install -r requirements.txt
```

### Migration the project

```bash
python manage.py migrate
```
### Running the project

```bash
python manage.py runserver
# running project in http://localhost:8000
```



# Use Case

- [Use-Cases](./presentation/Use-Case/Report.pdf)

# Diagrams
## Sequence Diagrams

### SignUp

![](presentation/diagram/Sequence-Diagrams/signup.png)

### Login

![](presentation/diagram/Sequence-Diagrams/login.png)


### Create Post

![](presentation/diagram/Sequence-Diagrams/createpost.png)


### Edit Post

![](presentation/diagram/Sequence-Diagrams/editpost.png)


### Write Comment

![](presentation/diagram/Sequence-Diagrams/writecommand.png)


### Like Post

![](presentation/diagram/Sequence-Diagrams/likepost.png)


### Remove Post
![](presentation/diagram/Sequence-Diagrams/removepost.png)


### Edit Profile
![](presentation/diagram/Sequence-Diagrams/editprofile.png)

### Change Password
![](presentation/diagram/Sequence-Diagrams/changepassword.png)

### Edit Comment
![](presentation/diagram/Sequence-Diagrams/editcomment.png)

## Remove Comment
![](presentation/diagram/Sequence-Diagrams/removecomment.png)


### Logout
![](presentation/diagram/Sequence-Diagrams/logout.png)


## Activity Diagram

![](presentation/diagram/Activity-Diagrams/Activity-diagram.png)

## Entity Relation Diagram

![](presentation/diagram/ERD/erd.png)

## Class Diagram

![](presentation/diagram/Class-Diagram/class-diagram.png)











