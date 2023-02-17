# LAB 1 `BEM`

## HUMAN BODY

```
.head
.head__eyes
.head__eye

.eye
.eye--closed


.body__neck
.body__arms
.body__arm

.arm
.arm__elbow
.arm__hand

.hand
.hand--clenched // сжатая кисть руки

.legs__leg

.leg
.leg__knees
.leg__knee

.knee
.knee--bent // согнутое колено
```

## Emmet

### Header

![header.png](img/header.png)

```scss
header.header>(nav.header__navigation.navigation>a.navigation__link*3)+a.header__phone.link>(svg.link__ico+span.link__text)
```


### Form


![img.png](img/form.png)

```scss
form.form>fieldset.form__fieldset>legend.form__legend+(label.form__label>input.form__input)*2+button.form__button
```

### Card

![img.png](img/cards.png)

```scss
.card>h3.card__title+(ul.card__list>li.card__item.item*4)*2
```

### Footer

![img.png](img/footer.png)

```scss
footer.footer>(h3.footer__title+(.footer__contacts>(a.footer__contact.contact>svg.contact__ico+p.contact__text)*2+ul.footer__links>li.footer__link.link*3)+p.footer__text)
```
