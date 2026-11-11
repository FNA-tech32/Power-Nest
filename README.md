# Power Nest

Landing page for **Power Nest**, a fitness studio in Fortaleza, Brazil. The site introduces the brand, the training space, upcoming events, membership plans, and how to get in touch.

Open `index.html` in a browser to view the page. Styles are served from `css/style.css`. The editable source is in `css/scss/`.

## Brand

The name used across the header, page title, and contact blocks is **Power Nest**.

## Sections

- **Entrada** — hero with the studio name, a short pitch, and a call to action
- **Sobre** — short introduction to the studio
- **Valores** — four highlights of the training space
- **Eventos** — the next three events, with dates
- **Modalidades** — membership plans: Mensal, Anual (marked as recommended), and Aula única
- **Galeria** — photos of the space; each image opens in a lightbox
- **Rodapé** — menu, address, alternative contact, and social links

## Contact

The address and the alternative contact are shown on the hero and again in the footer (`#contato`). The header and footer **Contato** links scroll to that block.

| | Detail |
| --- | --- |
| Studio | Power Nest |
| Address | Av. Santos Dumont, 880, Aldeota, Fortaleza - CE |
| Phone | (85) 3210-4480 |
| Email | contato@powernest.fit |

## Behavior

`script.js` handles three interactions:

- the mobile menu opens and closes from the header button
- gallery photos open in a modal and close from the backdrop or the close button
- sections fade in as they enter the viewport

## Project structure

```
index.html          Page markup
script.js           Menu, gallery modal, and scroll animation
css/style.css       Compiled stylesheet loaded by the page
css/scss/           SCSS source
img/                Icons and section images
```

## Credits

Check-mark icons are from Freepik via Flaticon. The page layout is based on the original academia landing page by Ariane Morelato.
