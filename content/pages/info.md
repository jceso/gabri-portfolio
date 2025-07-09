---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: ''
    media:
      type: ImageBlock
      url: /images/IMG_20220712_094706.jpg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
    title: >-
      SONO NATO IL 19 NOVEMBRE 2001SONO ORIGINARIO DI CASTELLUCCIO INFERIORE
      (PZ) MA DOMICILIO A PERUGIAHO LA PATENTE B E SONO AUTOMUNITO
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo4.svg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Logo five
        caption: Logo five
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: ''
    items:
      - type: Label
        label: C
      - type: Label
        label: Java
      - type: Label
        label: JavaScript
      - type: Label
        label: Python
      - type: Label
        label: Kotlin
      - type: Label
        label: R
      - type: Label
        label: PostgreSQL
      - type: Label
        label: MongoDB
      - type: Label
        label: MySQL
        url: ''
      - type: Label
        label: HTML
        url: ''
      - type: Label
        label: CSS
        url: ''
      - type: Label
        label: XML
        url: ''
      - type: Label
        label: GitHub
        url: ''
      - type: Label
        label: Android Studio
        url: ''
      - type: Label
        label: Web Programming
        url: ''
      - type: Label
        label: Android Development
        url: ''
      - type: Label
        label: Problem Solving
        url: ''
      - type: Label
        label: Gestione di progetti in team
        url: ''
      - type: Label
        label: Capacità di adattamento e rapidità di apprendimento
        url: ''
    title: Competenze
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: ''
        text: >+
          <div style="text-align: center">***Tirocinio***</div>


          **Weedea Srl, Perugia (PG)  |  Novembre 2023 - Febbraio 2024**


          *   Studio, test e implementazione di software per la gestione dei
          segreti di uno o più servizi all’interno di un container Docker

          *   Scrittura di una documentazione step-by-step per l’utilizzo e
          implementazione di tale sistema e delle sue funzioni


          ***


          <div style="text-align: center">***Volontariato***</div>


          **ESN Perugia | Novembre 2021 - presente**


          *   Gestione di lavori di gruppo, tramite organizzazione e attività di
              team building
          *   Manutenzione e gestione di app e sito web

          *   Supporto e interessamento a funzioni di tipo comunicativo e con
          rispetto di branding e regolamenti esterni

          *   Gestione e cura dei rapporti con enti e realtà esterne o interne
          alla rete ESN

        styles:
          self:
            textAlign: left
        title: Esperienze
      - type: FeaturedItem
        subtitle: ''
        text: |
          **Università degli studi di Perugia**

          *   Laurea Triennale in Informatica con Votazione 97/110
          *   *Settembre 2020 - Aprile 2025*

          ***

          **IIS De Sarlo - De Lorenzo | Lagonegro (PZ)**

          *  Liceo Scientifico opzione Scienze Applicate con votazione 83/100
          *  *Settembre 2015 - Giugno 2020*
        styles:
          self:
            textAlign: left
        title: '  Formazione'
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    title: Lingue
    subtitle: ''
    items:
      - type: Label
        label: Italiano - Madrelingua
        url: ''
      - type: Label
        label: Inglese - B2 Certificato
        url: ''
      - type: Label
        label: Portoghese - Base
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        textAlign: center
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---
