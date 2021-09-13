# **Yuliya Ivanova**
### JavaScript Developer

## Contacts

* Location: Gdansk, Poland
* Telegram: @liantras
* Email: artyulian@gmail.com
* GitHub: [yulian-dev](https://github.com/yulian-dev)
* LinkedIn: [Yuliana Ivanova](https://www.linkedin.com/in/yuliana-ivanova/)

## About Me

> I have been in IT for over 6 years,
> and for more than 1.5 years I've been doing layout for commerce.
> Programming is my passion,
> and I plan to grow up to a senior developer position within a few years.

## Skills

* HTML/CSS (Bootstrap, Flexbox)
* JavaScript
* React
* Git

## Code Example

```
const addEventListenersToRemoveButtons = () => {
    let removeButtons = document.getElementsByClassName('todo-remove');
    for (let button of removeButtons) {
        if (!button.getAttribute('data-event-click')) {
            button.addEventListener('click', () => {
                let id = button.parentElement.getAttribute('data-id');
                let todo = document.querySelector(`[data-id='${id}']`);
                todo.remove();
            });
            button.setAttribute('data-event-click', 'true');
        }
    }
}
```

## Experience

The first site I created: [Sarmont Studio](https://sarmontstudio.by/) and several layout projects on Bootstrap and Flexbox.

## Education

I had successfully completed the course [**"Front End Developer"**](https://www.linkedin.com/posts/yuliana-ivanova_teachmeskills-frontend-activity-6798999717515792384-uEl2) (208 academic hours) by [TeachMeSkills](https://teachmeskills.by/) in May 2021.

University: [Sukhoi State Technical University of Gomel](https://en.gstu.by/), Economics and Humanities Faculty

## English

**B1** (speaking and writing)