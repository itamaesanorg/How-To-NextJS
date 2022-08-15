We will create the components folder, but we will called: "bento", but why?
We will work as well as sushi is made and organized.

At the top of the folder, called "00 ..." will be the Headers, Menus... and all kind of infraestructure code, then by levels, as the guidelines on the officia repo says:

    01: 🍚, Cook rice. <- Prepare all your pages.
    02: 🧂, Mix Vinegar, Oil, Sugar & Salt.
    03: ⏲,  Cook until sugar is dissolved.
    04: 🥣, Stir into rice.
    05: 🐟, Prepear fillings.
    06: ⬛️, Put Nori on a bamboo mat.
    07: ⬜️, Put rice with hands.
    08: 🔲, Spride rice over the nori.
    09: 🥓, Lay the filling.
    10: 🎋, Roll the bamboo mat and press.
    11: 🔪, Cut with wet knife.
    12: 🍣, Enjoy!

    12 (real), 13, 14 and 15 steps above are optional.

So in this case you will see on the beta version of the website, the following folder structure:

    How to
    ├── 01 Sushisho (SushiJS Component, Main Menu)
    │   ├── Sushisho.tsx
    │   └── index.ts
    ├── 02 SushishoUsed (SushiJS Component, Main Menu in other pages, not homepage)
    │   ├── SushishoUsed.tsx
    │   └── index.ts
    ├── 03 Sushiten (SushiJS Component, Second Menu)
    │   ├── Sushiten.tsx
    │   └── index.ts
    ├── 04 SushitenUsed (SushiJS Component, Second Menu in other pages, not homepage)
    │   ├── SushitenUsed.tsx
    │   └── index.ts
    ├── 05 Bento (SushiJS Component, Welcome text and description, H1 and H2)
    │   ├── Bento.tsx
    │   └── index.ts
    ├── 06 Arubamu (SushiJS Component, Box Image)
    │   ├── Arubamu.tsx
    │   ├── ClientImageA.jpg
    │   ├── ClientImageB.jpg
    │   ├── ClientImageC.jpg
    │   └── index.tsx
    ├── 07 Do (SushiJS Component, Case Study)
    │   ├── CaseStudyComapnyA
    │   │   ├── BrandImageA.png
    │   │   ├── BrandImageB.png
    │   │   └── BrandImageC.png
    │   ├── CaseStudyComapnyB
    │   │   ├── BrandImageA.png
    │   │   ├── BrandImageB.png
    │   │   └── BrandImageC.png
    │   └── CaseStudyComapnyC
    │       ├── BrandImageA.png
    │       ├── BrandImageB.png
    │       └── BrandImageC.png
    ├── 08 Bijutsukan (SushiJS Component, Our history)
    │   ├── AboutUsImageA.jpg
    │   ├── AboutUsImageB.jpg
    │   └── AboutUsImageC.png
    ├── 09 Burando (SushiJS Component, Company logos for slider)
    │   ├── LogoCompanyA.png
    │   ├── LogoCompanyB.png
    │   └── LogoCompanyC.png
    ├── 10 Container (The famous container)
    │   ├── Container.tsx
    │   └── index.ts
    ├── 11 Izakaya (SushiJS Component, toggle dark mode)
    │   ├── Izakaya.tsx
    │   └── index.ts
    ├── 12 Sabisu (SushiJS Component, Our services pasges content)
    │   ├── Service 01
    │   │   ├── ImageService0101.jpg
    │   │   ├── ImageService0102.jpg
    │   │   ├── ImageService0103.jpg
    │   │   └── textservicetouse.md
    │   ├── Service 02
    │   │   ├── ImageService0201.jpg
    │   │   ├── ImageService0202.jpg
    │   │   ├── ImageService0203.jpg
    │   │   └── textservicetouse.md
    │   └── Service 03
    │       ├── ImageService0301.jpg
    │       ├── ImageService0302.jpg
    │       ├── ImageService0303.jpg
    │       └── textservicetouse.md
    ├── 13 ShashinArubamu like Arubamu but more modern (SushiJS Component, Box Image)
    │   ├── ShashinArubamu.tsx
    │   └── index.ts
    ├── 14 Tekisuto (text .md files here)
    │   ├── How we work.md
    │   ├── Some text.md
    │   └── What we do.md
    └── 15 Footer (The classic footer)
        ├── Footer.tsx
        └── index.ts

Well this is a Javascript project, we will use js instead of tsx, but don't worry about it.

 - <- [07 Learn NextJS, Head and _app, ITAMAESAN](https://github.com/itamaesanorg/How-To-NextJS/blob/main/07%20Learn%20NextJS%2C%20Head%20and%20_app%2C%20ITAMAESAN.md)
 - -> [09 Learn NextJS, Head for SEO and Bento, ITAMAESAN](https://github.com/itamaesanorg)
