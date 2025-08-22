---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'mI PRESENTO, SONO gABRIELE cESALI'
    subtitle: >-
      Sono un neolaureato in Informatica, con uno spiccato interesse per la
      programmazione e lo sviluppo web. L’esperienza Erasmus+ ha rafforzato la
      mia adattabilità e la comunicazione in contesti interculturali, competenze
      preziose per lavorare su progetti reali e innovativi. Cerco un contesto
      che mi dia l'opportunità di mettere in pratica le mie capacità in ambienti
      dinamici e stimolanti.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-20
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-three.md
      - content/pages/projects/project-four.md
      - content/pages/projects/project-two.md
      - content/pages/projects/project-one.md
      - content/pages/projects/project-five.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-10
          - pb-5
          - pl-4
          - pr-4
        textAlign: left
    subtitle: ''
    title: Progetti
---
