---
type: PageLayout
title: About
colors: colors-a
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >
      I have had a deep passion for music since childhood. In 2019, I saw Alan
      Walker making music with a computer and found it interesting, which led me
      to begin learning music on my own.


      I independently released my first single as my stage name FRESCADE, 'Low
      Spirits,' in July 2022. Before the release of 'Low Spirits,' I released
      some unofficial remixes on my YouTube and SoundCloud channels. In August
      2023, I released another single, "When Time Decays," featuring Robert
      Crowell. I prioritize quality over quantity in my work, and my music
      reflects life. While my main genre is Future Bass, I enjoy exploring
      dubstep and trap music.
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
      url: /images/PXL_20230922_021115792.jpg
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
  url: /images/matt-wang-IKbpXrInCJY-unsplash.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 100
---
