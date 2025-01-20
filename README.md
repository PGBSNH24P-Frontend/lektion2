---
author: Lektion 2
date: MMMM dd, YYYY
paging: "%d / %d"
---

# Lektion 2

Hej och välkommen!

## Dagens agenda

1. Frågor och repetition
2. Genomgång av övningar
3. Introduktion till layouts
   - Position egenskapen
   - Display egenskapen
   - flexbox
   - grid
4. Övning med handledning
5. Genomgång av övningar
6. Quiz frågor

---

# Position egenskapen

Bestämmer hur ett element positioneras.

- `static` - default, följer förälder och påverkas inte av `left` m.m
- `relative` - följer förälder och kan påverkas av `left` m.m
- `absolute` - ignorerar hierarki och kan påverkas av `left` m.m
- `fixed` - ignorerar hierarki, relativ till 'viewport' och kan påverkas av `left` m.m
- `sticky` - <https://css-tricks.com/position-sticky-2/>

---

# Display egenskapen

- Välj mellan `block`, `inline` och fler
- Bestämmer hur layout skall hanteras för barn-elementen.

- `inline` - default, fortsätter på samma rad, kan inte applicera `width` eller `height`
- `inline-block` - samma som inline men accepterar `width` och `height`
- `block` - börjar på ny rad och tar upp hela raden, accepterar `width` och `height`
- `grid` - applicerar grid regler på barn
- `flex` - applicerar flexbox regler på barn
- `none` - elementet visas inte alls

---

# Övning med handledning

Nu övar vi! Övningar ligger på GitHub.

Vi samlas och går igenom några av dem efteråt. Skriv ned övningar som är svåra eller som ni vill ha mer förklaring kring.

---

# Quiz frågor

- Vad är element?
- Vad är syntaxen för element-attributer?
- Ge två exempel på selectors med typ och syntax.
- Vilken tag används för att länka till en separat CSS fil?
- Vad gör `position: absolute`?
- Vad gör `display: inline`?
- Hur applicerar man flexbox regler på ett element?
- Vad gör `justify-content`?
- Vad gör `align-items`?
- Vad gör `grid-template-rows`?
- Hur skiljer sig `gap` från `margin`?
