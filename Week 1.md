# Opstarten bij 100% Leiden
## Maandag 3 februari
- Teamleader, taken, inloggegevens etc.
- Meer leren -> Wordpress
- Dropbox

<img src="https://github.com/user-attachments/assets/74dc6bab-240d-4900-857b-a4442b8e5092" width="300px">

<img src="https://github.com/user-attachments/assets/3450910a-74b2-491f-8eb4-7af3d60de9ab" width="300px">

Ik heb de inhoud van de NEI-landingspagina in WPBakery geplaatst en basisstyling toegepast.

## Dinsdag 4 februari

Als eerst had ik een stand-up vandaag. Darna heb  ik de landingspagina gestyled.

<img src="https://github.com/user-attachments/assets/158db5ac-c4d3-4af7-9b11-40ac7fc8194c" width="300px">

<img src="https://github.com/user-attachments/assets/f088c4ea-9982-476a-9760-8648c6eaefb8" height="300px">

- [x] Responsive maken


<img src="https://github.com/user-attachments/assets/86cab61d-b8c7-48ac-b47d-4717d067ef12" width="300px">


## Wwoensdag 5 februari
**09:12**: Ik ben er achter gekomen dat alle styling die ik heb toegepast inline styling is (daarom stond er dus !important 🤦‍♂️ ). Dit ga ik nu aanpasssen. 

**09:38**: ⬆️ no worries, het was wel gewoon goed. Ik ga weer verder met de media queries

**Kind & aandacht**
- [x] Intro text een max width geven; hoe roep ik het aan in de css?
- [ ] Divider in section 1 langer
- [x] Bulletpoints in de list item zijn custom en nu veel te groot, kan ik het verkleinen?
- [x] Image in de blocks dezelfde height meegeven als de container
- [x] Tekst in de last section hoger zetten


**To do voor morgen:**

- [x] blocks centreren
- [x] afbeelding esther background dubbel

<img src="https://github.com/user-attachments/assets/76fe4f71-7b0b-47e1-ab52-5d79cc8fce1b" width="300px">

<img src="https://github.com/user-attachments/assets/b5764733-9830-4f87-b471-c1d4ce011965" width="300px">

## Donderdag 6 februari
- Ik heb mijn do do lijstje afgewerkt!
- De `!important` is vaak nodig 👎

  
- `align-items: center` en `display: flex` werken niet. 
- ⬆️ Werkt wel:
Het divje zit in een div. De geneste div kan je geen class geven dus moet je het zo aanroepen: `classnaam div:first-of-type'

### URL check
Ik heb de sitemap URL's gecheckt of er ergens verwijst wordt naar ' resengo'. Dat heb ik gedaan door `/sitemap.xml` achter de site te plakken, je krijgt dan alle linkjes te zien. 

first
```
    .txt-sctn-1  > div {
        border: none;
    }
``` 
