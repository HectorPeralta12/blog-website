# 🚀 Django Blog Website

<div align="center">

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

*A complete and functional blog built with Django* ✨

</div>

---

## 📝 What is this?

A blog website developed with **Django** that allows users to create, edit, and manage blog posts with a complete authentication system.

## 🌟 Main Features

<table>
<tr>
<td width="50%">

### 📚 Post Management
- **Create** new posts
- **Read** existing posts  
- **Edit** your posts
- **Delete** posts

</td>
<td width="50%">

### 👤 User System
- **User registration**
- **Secure login/logout**
- **Author profiles**
- **Edit permissions**

</td>
</tr>
</table>

---

## ⚡ Quick Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/HectorPeralta12/blog-website.git
cd blog-website

# 2️⃣ Create virtual environment
python -m venv blog_env
source blog_env/bin/activate  # On Windows: blog_env\Scripts\activate

# 3️⃣ Install Django
pip install django

# 4️⃣ Setup database
python manage.py makemigrations
python manage.py migrate

# 5️⃣ Run the server!
python manage.py runserver
```

🎉 **Ready!** Visit `http://127.0.0.1:8000/`

---

## 🧪 Testing

Run the complete test suite:

```bash
python manage.py test
```

✅ **Includes tests for:**
- Post model functionality
- CRUD operations
- User authentication
- URL routing
- Template rendering

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3, Django Templates
- **Database:** SQLite
- **Authentication:** Django Auth System

---

## 🚀 Features in Action

### Create a Post
1.  Log in to your account
2.  Click "New Blog Post"
3.  Fill out the form
4.  Save your post

### Edit a Post
1. Go to post detail
2. Click "Edit Blog Post"  
3. Update content
4. Save changes

---

## 🙏 Acknowledgments

Special thanks to **William S. Vincent** and his book **Django for Beginners** for the excellent tutorial that inspired this project!

---

<div align="center">

⭐ **If you found this project helpful, please give it a star!** ⭐


</div>
