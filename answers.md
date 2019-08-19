Question 1:
let = profilePic = document.querySelector('img')
profilePic.src = 'https://placebear.com/g/400/400'


Question 2:
let = skyPic = document.querySelector('#left-image > img')
skyPic.src = 'https://picsum.photos/id/543/325/225'

Question 3:
bearHeading = document.querySelector('h1')
bearHeading.innerHTML = "Stanley Sham"

Question 4:
employmentTitle = document.querySelector('#employment > h3')
employmentTitle.innerText = "Funemployment"

Question 5:
bodyElement = document.querySelector('body')
bodyElement.style.backgroundColor = 'purple'

Question 6:
let highlight = document.querySelectorAll('.highlight')
for (let i = 0; i < highlight.length; i ++) {
	highlight[i].style.color = 'black'
}

Question 7:
allH1 = document.querySelectorAll('h1')
allH1[0].style.fontFamily = 'monospace'
There is only 1 h1 in the whole page

Question 8:
let roundIcons = document.querySelectorAll('.action-icon-bg')
for (let i = 0; i < roundIcons.length; i++) {
	roundIcons[i].style.backgroundColor = 'purple'
}

Question 9:
let nameField = document.querySelector('#name')
nameField.placeholder = 'Identify Yourself'

Question 10:
let messageField = document.querySelector('#message')
messageField.placeholder = 'State your business'

Question 11:
nameField.value = 'Your nemesis'

Question 12:
let emailField = document.querySelector('#email')
emailField.value = 'koalathebear@gmail.com'

Question 13:
let submitButton = document.querySelector('#submit')
submitButton.value = 'En Garde!'

Question 14:
submitButton = document.querySelector('#submit')
submitButton.disabled = true

Question 15:
personalInfo = document.querySelector('.bio-info')
personalInfo.remove()
