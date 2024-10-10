---
type: PageLayout
title: About
colors: colors-a
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: "Muntasir Mahmud, known as\_[FRESCADE](https://open.spotify.com/artist/5YfpwNujtLaNAzONsvcO9G)\_is a Bangladeshi Electronic Dance Music producer.\n\nSince 2019, he's been crafting tunes from the depths of his heart, expressing untold sadness and emotions through his music.\n\nIn 2022, he released his first single \"Low Spirits,\" a track that resonated deeply with listeners. But even before that,\_[FRESCADE](https://open.spotify.com/artist/5YfpwNujtLaNAzONsvcO9G)\_had garnered attention with several remixes.\n\nHis goal is to connect with fans who can relate to his songs, especially those struggling with loneliness, depression, or tough times. Through his heartfelt melodies, he seeks to offer solace and a sense of companionship, just like music has been to him in times of loneliness.\n\nFor\_[FRESCADE](https://open.spotify.com/artist/5YfpwNujtLaNAzONsvcO9G)\_music is more than beats. It's a language to express his deepest feelings. He pours his heart into every piece, making music that speaks to the soul.\n"
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
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    media:
      type: ImageBlock
      url: /images/IMG_5476-01~2.jpeg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
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
        submitLabel:
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
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
---
