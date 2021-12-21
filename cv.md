# Yuri Borysiuk

## Contact information
Location: Brest, Belarus

Phone: (+37529) 820 18 50

Email: yuri.borysiuk@gmail.com

LinkedIn: [yuri-borysiuk](https://www.linkedin.com/in/yuri-borysiuk/)

GitHub:  [YuriBorysiuk](https://github.com/YuriBorysiuk)

---

## About Me
I'm looking for a junior front-end developer position. I work as a design engineer in JOFRE.

I've been studying the frontend on my own for about 2 years, on average 1-2 hours a day.

Communication skills and responsibility are developed, stress-resistant, I am not afraid of difficult and unsolvable, at first glance, tasks. Capable student. I am open to new opportunities, knowledge and skills. Motivated, hardworking.

---

## Skills
- languages and technologies: JS (ES6), HTML5, CSS3, SASS, SCSS;
- libraries / frameworks: Bootstrap, React (Basics);
- used tools and skills: VS Code, Git (GitDesktop, terminal), Photoshop, Figma, Webpack, Node, npm, Firebase, Trello, principles of adaptive and cross-browser layout, Mobile First, BEM methodology, Agile, Kanban.

### Examples of recent work:
Date: September 2021

I study at RS School courses

Link: https://rs.school/

Date: August 2021

Title: Hot burgers

Summary: Create an app for ordering burgers using the React library. Study project

Role: React developer.

Technologies: **React, Stylus, Firebase, Git**

Link: https://github.com/YuriBorysiuk/React_project

Date: July 2021

Title: Promo page
Description: Layout of a promo-site advertising a BMW car.

Role: Frontend developer, HTML coder.

Technologies: **HTML, SASS, JavaScript, Figma, Git**

Link: https://github.com/YuriBorysiuk/Promo_page_BMW/tree/dev

Date: June 2021

Title: Marathon from Vladilen Minin

Description: Passed a 5-day marathon from Vladilen Minin on which 5 projects were completed (https://github.com/YuriBorysiuk/Marathon-minin):
1. Gallery from cards (https://jsfiddle.net/nasgool/n3je7mhb/)
2. Working with Drag & Drop (https://jsfiddle.net/nasgool/pq9avofh/)
3. Picture slider (https://jsfiddle.net/nasgool/vh0x81sy/)
4. Hover Board (https://jsfiddle.net/nasgool/26ags90f/1/)
5. AIM Game (https://jsfiddle.net/nasgool/pztv4Lbj/)

Role: Frontend developer.

Technologies: **HTML, CSS, JavaScript, Git**

Link: https://github.com/YuriBorysiuk/Marathon-minin

---

## Code Example

```javascript
const input = '1,3,5,4,8,12,13,14,15,22,16,1'//1, 3-5, 8, 12-16, 22

const sortFunc = (a, b) => {
    if (a < b) {
        return -1
    }
    if (a > b) {
        return 1
    }
    return 0
}

const getUnicValues = (data) => {
    const dataSet = new Set(data)
    return [...dataSet]
}

const inputData = input.split(',').map(page => parseInt(page)).sort(sortFunc).slice(0, 99)
const unicInputData = getUnicValues(inputData)
const dataIntervals = []
const interval = []

for(let idx = 0; idx < unicInputData.length; idx++){
    const currentValue = unicInputData[idx]
    const nextValue = idx + 1 ? unicInputData[idx + 1] : null
    if (nextValue - 1 === currentValue) {
        interval.push(currentValue)
    } else {
        interval.push(currentValue)
        dataIntervals.push([...interval])
        interval.length = 0
    }
}

const getOutputString = (data) => {
    const pageIntervals = data.map((value) => {
        if (value.length > 1) {
            return `${value[0]}-${value[value.length - 1]}`
        }
        return value[0]
    })
    return pageIntervals.join(',')
}
console.log('output: ', getOutputString(dataIntervals))
```

---

## Education
1. 2008-2012, Belarusian State University of Informatics and Radioelectronics.
Computer Technology, Industrial Electronics, Electronics Engineer

1.	JS, CSS, HTML, Git video courses on YouTube channel Glo Academy
2.	JS video on YouTube channel Vladilen Minin
3.	JavaScript https://learn.javascript.ru/
4.	Course React JS “React 001” by Василий Муравьев
1. RS Schools Course "JavaScript/Front-end. 2021Q3" (interrupted training at the end of Stage1)
1. RS Schools Course "JS/FE Pre-School 2022" (in progress)

---

## Languages
English - A2

Polish  - Intermediate

Russian - Native
