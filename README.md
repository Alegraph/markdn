# Aleh Ivanou
 
## Contacts
* Email: cosarrtelan@gmail.com
* GitHub: AI-Oleg

## About Me
I am a communicative and determined developer with some experience in web development (freelance). My strengths include teamwork, quick learning, perseverance, and a drive for self-improvement. I have experience with programming languages such as JavaScript, HTML, CSS, Python, C, and Kotlin.

## Skills
- Programming languages:
  - JavaScript
  - Python
  - C
  - Kotlin
- Jinja template
- Platforms: Node.js, Flask
- Methodologies: Agile
- Version control systems: Git
- Development tools: Visual Studio Code, Sublime Text, GitHub, WebStorm, PyCharm
- Play the guitar
- Make an infinite number of cups of tea
 
## Примеры кода *Python*
```
app = Flask(__name__)
app.secret_key = 'my-super-secret-phrase-I-dont-tell-this-to-nobody'

class my_Form(FlaskForm):
    name = StringField('Имя пользователя')
    phone = StringField('Телефон пользователя')
    age = IntegerField('Возраст')
    bio = TextAreaField('Информация обо мне')
    password = PasswordField('Ваш пароль')
    submit = SubmitField('Поехали!')

@app.route('/myform', methods=['GET', 'POST'])
def myform():
    form = my_Form()
    if request.method == 'GET':
        return render_template('myform.html', form=form)
    return form.name.data


if __name__ == '__main__':
    app.run(debug=True)
```

## Education 
- Мechanical engineer *BelGUT*
- HTML и CSS *Netology*
- Python, JavaScript *Stepik*

## Languages:
* -English - Per-intermediate
* -Deutsche - Basic
* -Russian - Native
