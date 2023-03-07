# Valera Litvin

---

## Contact info

---

- BY, Minsk
- Telegram: @Litvin_craftstudio
- Discird: ValerA108
- E-mail: 7000108v@gmail.com
- GitHub: ValerA108

## About Me

---

I've always been attracted to the technical sciences. By education, I am an energy engineer and economist. I worked in an international transport company, a leader in the European freight market.
In 2014 I opened my advertising agency. It had closing in 2021.
My interest in IT began with learning Linux. Slowly I switched to learning HTML and CSS. I decided for myself that I wanted to develop in this direction. It allows me to work for the outside market from anywhere in the world where there is the internet.

My strengths:

- Quick learning curve
- Hard work
- Team play
- Delegation
- Assiduity and learnability
- I find it easy to communication large customers
- I try to develop 1-2 new skills per year

## Skills

---

- HTML
- CSS
- JS Basics
- Version control: Git (remote service GitHub)
- Windows OS, Linux (Garuda Gnome, Mint, KDE-Neon, Kali, Whonix, Manjaro), MacOS
- Editors: Sublime, VSCode,
- Design (Adobe Photoshop, CorelDraw, Krita)
- Sound design (Ableton Live)

## Code examples

---

```javascript
export function productTabsSwitcher() {
  const tabSection = document.querySelector(".product-tabs");

  const productTabs = document.querySelectorAll(".product-tabs__top-item");
  const productContent = document.querySelectorAll(
    ".product-tabs__content-item"
  );

  if (tabSection) {
    productTabs.forEach(onTabClick);
    function onTabClick(item) {
      item.addEventListener("click", () => {
        let currTabBtn = item;
        let tabId = currTabBtn.getAttribute("href");
        let currTab = document.querySelector(tabId);

        if (!currTabBtn.classList.contains("active")) {
          productTabs.forEach(function (item) {
            item.classList.remove("active");
          });
          productContent.forEach(function (item) {
            item.classList.remove("active");
          });

          currTabBtn.classList.add("active");
          currTab.classList.add("active");
        }
      });
    }
    document.querySelector(".product-tabs__top-item:nth-child(3)").click();
  }
}
```

## Education

---

- Minsk State Energy College

- Belarusian National Technical University

## Experience

---

[My CV-page](https://valera108.github.io/rsschool-cv/cv)

## Languages

---

- Russian
- Polish
- English - A2 (While working for a transportation company I communicated with customers from Europe. Business correspondence, documentation, customs clearance of cargo, invoice, packing list)
- Test-english.com - B1
