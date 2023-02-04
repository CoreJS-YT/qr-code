# Frontend Mentor - QR code component

## Description

Aqui hise el reto de [**QR Code Componemt**](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub) terminado en (1 hrs)

## Commits

### **Commit 1 - ( *Iniciando El Reto* )**
![Carpeta Del Proyecto](./images/Captura%20de%20pantalla_20230203_100331.png)
Archivos, Carpetas y Imagenes que voy a utilizar en el reto.

### **Commit 2 - ( *HTML Terminado* )**

Este es el codigo que use en reto en html

```html
<main class="card">
    <div class="card__preview">
      <img src="./images/image-qr-code.png" alt="QR Code" class="card__preview__image">
    </div>
    <div class="card__description">
      <h1 class="card__description__title">Improve your front-end skills by building projects</h1>
      <p class="card__description__desc">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </main>
```

### **Commit 3 - ( *CSS Terminado* )**

Este es Codigo que use en el reto en css

```css
:root {
    /* Colors */
    --White: #ffffff;
    --Light-Gray: #d6e2f0;
    --Grayish-Blue: #7b879d;
    --Dark-Blue: #1f3251;
    /* Fonts */
    --Font-Oufit: 'Outfit', sans-serif;
}

* {
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}

body {
    font-family: var(--Font-Oufit);
    background-color: var(--Light-Gray);
    font-size: 15px;
}

.card {
    width: 320px;
    height: 500px;
    background-color: var(--White);
    margin: 20px auto;
    overflow: hidden;
    border-radius: 12px;
}

.card__preview {
    width: 290px;
    height: 290px;
    overflow: hidden;
    border-radius: 12px;
    margin: 17px 17px 20px 17px;
}

.card__preview__image {
    width: 100%;
    height: 100%;
}

.card__description {
    width: 320px;
    height: 191px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.card__description__title {
    font-weight: 700;
    font-size: 1.43em;
    color: var(--Dark-Blue);
    width: 250px;
    height: 50px;
    margin: 0 auto 15px auto;
}

.card__description__desc {
    width: 230px;
    height: 50px;
    font-weight: 400;
    font-size: .95em;
    color: var(--Grayish-Blue);
    text-align: center;
}

@media (min-width: 700px) {
    .card {
        margin: 100px auto;
    }
}
```
