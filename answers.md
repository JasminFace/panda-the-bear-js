1.
    var img = document.querySelector('.profile-image')
    img.src = "https://placebear.com/g/400/400"


    var img2 = document.querySelector('.picture')
    img2.src = "https://placebear.com/g/325/225"

2.
    var heading = document.querySelector('h1.highlight')
    heading.innerText = 'Jasmin'

3.
    var experience = document.querySelector('#employment h3.info-title')
    experience.innerText = 'Experience'

4.
    var body = document.querySelector('body')
    body.style.backgroundColor = 'blue'

5.
    var highlights = document.querySelectorAll('.highlight')
    highlights.forEach(element => element.style.backgroundColor = 'blue')

6.
    var headerFont = document.querySelector('h1')
    headerFont.style.fontFamily = 'monospace'

7.
    var icon = document.querySelectorAll('.action-icon-bg')
    icon.forEach(element => element.style.backgroundColor = 'red'

8.
    var formName = document.querySelector('#name')
    formName.placeholder = 'Identify Yourself'

9.
    var message = document.querySelector('#message')
    message.placeholder = 'State Your Business'

10.
    formName.value = 'your nemesis'

11.
    var email = document.querySelector('#email')
    email.value = 'koalathebear@gmail.com'

12.
    var submit = document.querySelector('#submit')
    submit.value = 'En garde!'

13.
    submit.disabled = true

14.
    var bio = document.querySelector('.bio-info')
    bio.parentNode.removeChild(bio)