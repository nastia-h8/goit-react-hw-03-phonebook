# Contacts book

`upd:`

- додано можливість зберігання контактів телефонної книги в localStorage.
- використано методи життєвого циклу.

1. Застосунок складається з форми і списку контактів.
2. Реалізовано додавання імені, телефону контакту та відображення списку
   контактів.
3. Додано поле пошуку, яке можна використовувати для фільтрації списку контактів
   за ім'ям.
4. Користувачеві заборонено додавати контакти, імена яких вже присутні у
   телефонній книзі.
5. Користувачеві дозволено видаляти раніше збережені контакти.
6. Застосунок не зберігає контакти між різними сесіями.

- Для генерації ідентифікаторів використано `nanoid`
- Для валідації інпутів використано `yup`
- Для створення форми використано `formik`
- Стилізація - `styled-components`