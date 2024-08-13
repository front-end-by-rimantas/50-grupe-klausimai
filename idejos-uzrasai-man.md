# Topics

-   DOM + localStorage + page refresh / events
    -   DOM: string HTML -> innerHTML
    -   localStorage: getItem(key), setItem(key, value) + JSON
    -   events: click, submit, .....
-   keyboard events (listeners)
-   pats react (x2)

const person = {}

const x = JSON.stringify(person)
localStorage.setItem('database', x)

const db = localStorage.getItem('database')
const y = JSON.parse(db)
