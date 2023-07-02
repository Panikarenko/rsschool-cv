CV
Name: Daryna
Surname: Panikarenko
Phone number: 722704980
Email: danya.panikarenko@gmail.com
Telegram: @D_artagnanna
Discord: darynapanikarenko

About me:
I am a student studying computer science. I love coding and I want to become a professional Front-end developer!

Skills:
HTML, CSS, JavaScript, Git

Code Example:
const currentDate=document.querySelector(".current-date"),
prevNextIcon=document.querySelectorAll(".icons span"),
button=document.querySelector(".inst-button"),
infoWrapper=document.querySelector(".info-wrapper"),
daysTag=document.querySelector(".days");

button.addEventListener("click", () => {
    if (infoWrapper.classList.contains('info-inactive')){
        infoWrapper.classList.remove('info-inactive');
        button.textContent ="Hide: instrukcje do sprzątania";
    }
    else{
        infoWrapper.classList.add('info-inactive');
        button.textContent ="Show: instrukcje do sprzątania";
    }
})

let date=new Date(),
currYear=date.getFullYear(),
currMonth=date.getMonth();

const months=["January", "February", "March", "April", "May", "June", "July",
                "August", "September", "October", "November", "December"]

Work Expirience:
InPost: Operator

Education:
Medicus, Assistant director of film and television production
University of Adam Mickiewicz, Computer Science(Currently)

Languages:
English-B1
Ukrainian-C1
Russian-C1
Polish-B2