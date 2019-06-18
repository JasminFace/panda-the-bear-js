PART 1

1.
    var img = document.querySelector('.profile-image');
    img.src = "https://placebear.com/g/400/400";


    var img2 = document.querySelector('.picture';)
    img2.src = "https://placebear.com/g/325/225";

2.
    var heading = document.querySelector('h1.highlight');
    heading.innerText = 'Jasmin';

3.
    var experience = document.querySelector('#employment h3.info-title');
    experience.innerText = 'Experience';

4.
    var body = document.querySelector('body');
    body.style.backgroundColor = 'blue';

5.
    var highlights = document.querySelectorAll('.highlight');
    highlights.forEach(element => element.style.backgroundColor = 'blue');

6.
    var headerFont = document.querySelector('h1');
    headerFont.style.fontFamily = 'monospace';

7.
    var icon = document.querySelectorAll('.action-icon-bg');
    icon.forEach(element => element.style.backgroundColor = 'red';

8.
    var formName = document.querySelector('#name');
    formName.placeholder = 'Identify Yourself';

9.
    var message = document.querySelector('#message');
    message.placeholder = 'State Your Business';

10.
    formName.value = 'your nemesis';

11.
    var email = document.querySelector('#email');
    email.value = 'koalathebear@gmail.com';

12.
    var submit = document.querySelector('#submit');
    submit.value = 'En garde!';

13.
    submit.disabled = true;

14.
    var bio = document.querySelector('.bio-info');
    bio.parentNode.removeChild(bio);

PART 2

Removing Elements from the DOM
1.
    var lies = document.querySelector('#time-travel').parentNode;
    lies.parentNode.removeChild(lies);

Adding Elements to the DOM
1.
    var pikachu = document.querySelector('#right-image').firstElementChild;
    var pc = document.querySelector('.portfolio-container').parentNode;
    pikachuClone = pikachu.cloneNode(true);
    pc.appendChild(pikachuClone);

2.
    var pikachu = document.querySelector('#right-image').firstElementChild;
    var pc = document.querySelector('.portfolio-container').parentNode;
    for (let i = 0; i < 10; i++) {pc.appendChild(pikachu.cloneNode())};

3.
    const listItem = document.createElement('li'); 
    const leftSpan = document.createElement('span');
    var lastUpdated = document.createTextNode('Page last updated on');
    leftSpan.appendChild(lastUpdated);
    listItem.appendChild(leftSpan);
    const dateSpan = document.createElement('span');
    var date = document.createTextNode(new Date());
    dateSpan.appendChild(date); listItem.appendChild(dateSpan);
    bio = document.querySelector('.bio-info'); bio.appendChild(listItem);