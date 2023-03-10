# Marley Medical Frontend Code Challenge

👋 Hello and thank you for your interest in Marley Medical!

As part of our interview process, we want to learn a bit more about your frontend technical skills.

In this engineering challenge you are being asked to build a relatively small React app which will help us assess your:

1. Technical competency with TypeScript, React, HTML/CSS, and GitHub
2. Comprehension of requirements and design specifications
3. Ability to quickly learn new libraries
4. Technical communication skills with another engineer

Depending on familiarity with web development and React, we would expect this challenge to take anywhere between two and four hours.

Once you have completed the challenge, please share the cloned repo with your point of contact at Marley Medical.

As always, please feel free to reach out with questions at any time.

## Problem Context

Patients new to Marley Medical must first consent to treatment with us before treatment can be administered. To consent to treatment, patients must agree to four legal documents:

1. New Patient Agreement
2. Informed Consent
3. HIPAA Notice
4. Receiving Texts and Emails

To streamline this process, Marley's clinical team has requested help automating this particular step in the patient journey.

After considerable collaboration with the team, it was determined that a UI feature be implemented to solve the problem.

## Instructions

As the lead frontend engineer on this project, you have been tasked with implementing the UI to solve the problem described above.

At a high-level, you are being asked to implement a small application which:

1. Informs the patient which documents they must agree to
2. Renders the text of each individual document, one at a time
3. Does not allow the patient to view the next document until they have agreed, via a checkbox, to the document currently rendered
4. Notifies the patient once all four documents have been agreed to
5. Serves patients accessing the application from a mobile browser

Please see the design specifications and demo below for additional context.

**Note:** Be sure to read the "Markdown", "Style Guide", and "Component Library" sections at the bottom of this document for relevant implementation help.

## Design Specifications

![marley_medical_fe_practical_spec](https://user-images.githubusercontent.com/4118615/224188439-5a2e22f1-95bf-4d27-9076-44728886c967.png)

## Feature Demo

https://user-images.githubusercontent.com/4118615/224188556-041901d9-c2d6-4a9f-beda-4cb3d2ac296d.mov

## Getting Started

To help get you started, we have scaffolded a small React application using [`create-react-app`](https://create-react-app.dev/docs/getting-started/#yarn).

In order to run the application, you will need [Node](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/) (or NPM) installed.

To install the necessary dependencies run:

```
yarn
```

To start the application run:

```
yarn start
```

Once running, the application will be accessible at `localhost:3000` in your browser.

## Style Guide

Admittedly, we are less concerned with pixel-perfect styling than we are your React implementation. As such, we ask that you not get too caught up with exact spacing (margin and padding).

After all, perfect is the enemy of good.

That said, we are including the following color palette to help speed your development:

- Page background ![#FFF](https://via.placeholder.com/15/FFF/000000?text=+) `#FFF`
- Body text ![#1A202C](https://via.placeholder.com/15/1A202C/000000?text=+) `#1A202C`
- Purple (Heading and Buttons) ![#5A38B2](https://via.placeholder.com/15/5A38B2/000000?text=+) `#5A38B2`
- Links ![#3182ce](https://via.placeholder.com/15/3182ce/000000?text=+) `#3182ce`
- Borders ![#DDD7CF](https://via.placeholder.com/15/DDD7CF/000000?text=+) `#DDD7CF`

## Component Library

Feel free to style the application with whatever component library you prefer, but be expected to be asked about your tooling selection later on.

For what it is worth, at Marley we use [Chakra](https://chakra-ui.com/) for most of our client-facing applications. As such, the design specifications and demo above were styled using Chakra.

## Markdown

Included in this project are four markdown files corresponding to the four legal documents patients must agree to before treatment.

You can find these four files within `src/markdown`. Naturally, the files are filled with lorem ipsum.

We have also included a dependency, `react-markdown`, which is essentially a React component that consumes and renders markdown.

We included both the files and the dependency to help speed your development, but please feel free to use another approach if you'd prefer.
