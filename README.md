# Estudio Cactus Fullstack Test

This is a test to validate the knowledge of the candidates for the position of developer at Estudio Cactus

## Stack

- React
- NextJS
- Firebase
- Tailwindcss

## Description

In this case the test consists of creating a 3d room configurator. In the following link you can see an example of how the configurator should look like: https://app.estudiocactus.com/visualizer.mp4

Following you have a detailed layout of the data needed to pass the test:

Base image url: https://firebasestorage.googleapis.com/v0/b/visualizer-new-devs-test.appspot.com/o/base.jpeg?alt=media&token=358ccdea-3cf9-4751-ae48-4631e4700554

Coordinates to draw the points over the base image:

```
.
└── firestore(/)
    └── points (collection)
```

List of all materials (TIP: You have to think about the right query to get all the materials for a specific point -> Firestore allows array-contains queries)

```
.
└── firestore(/)
    └── materials (collection)
```

The credentials for the Firebase connection:

```
{
  apiKey: 'AIzaSyC_JwpXS4uj9sRRDrbFAtalE1QulNTmKnw',
  authDomain: 'visualizer-new-devs-test.firebaseapp.com',
  projectId: 'visualizer-new-devs-test',
  storageBucket: 'visualizer-new-devs-test.appspot.com',
  messagingSenderId: '702664185241',
  appId: '1:702664185241:web:580752c50d570d0c89ef08'
}
```

## Requirements

1. Use ESlint, Prettier and StandardJS as linter
2. Use TypeScript
3. Code should be completely in english ( filenames, variables)

**IMPORTANT:** We won't accept code with harcoded databaes values (e.g. document id's to make comparisons, url's for background images etc)

## How to start?

1. Create a new Next.js project
2. Make at least 1 first commit with the original code, to see the init hour.
3. Make individiual commits for each block you create. The last commit marks the end.
4. Send us a link to your repo.
5. Deploy your repo to vercel.
6. Send us a link to the deployed project.

## What we value?

- Simplicity of the solution
- Organization and clean code
- Decisiones about client/server rendering
- Cache management
- Mobile first & RWD
- Git usage
- Web Performance Optimization
- Technical knowledge
- Layout knowledge (HTML5 y CSS3)
