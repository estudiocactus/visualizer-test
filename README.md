# Estudio Cactus Fullstack Test

This is a test to validate the knowledge of the candidates for the position of fullstack developer at Estudio Cactus

## Stack

- React
- NextJS
- Firebase
- Tailwindcss

## Description

In this case the test consists of creating a 3d room configurator. In the following link you can see an example of a configurator that we built: https://app.estudiocactus.com/configurador.mp4

Following you have a detailed layout of the data needed to pass the test:

Base image url: https://firebasestorage.googleapis.com/v0/b/porcelanosa-partners-spaces.appspot.com/o/projects%2FdorptVQTHsbkYC60NSlt%2Fscenes%2F1567170849457-base?alt=media&token=cf8bcee2-bf89-4fd9-8bfd-9d4462348844

Coordinates of the points over the base image:

```
.
└── firestore(/)
    └── points
```

List of materials

```
.
└── firestore(/)
    └── materials
        └──{pointId}
```

The credentials file for firebase is located at

```
.
└── firebase
    └── config
```

The page should be created in the following file, the initial styles and typography(/styles/global.css) are already set:

```
.
└── pages
    └── index.js
```

The functionality should be the following

https://app.estudiocactus.com/configurador.mp4

## Requirements

1. Use StandardJS as a linter
2. Code should be completely in english ( filenames, variables)

## How to start?

1. Create a new repo utilizing this one as a base(without forking)
2. Make at least 1 first commit with the original code, to see the init hour.
3. Make individiual commits for each block you create. The last commit marks the end.
4. Send us a link to your repo.
5. Deploy your repo to vercel.
6. Send us a link to the deployed project.

## What we value?

- Simplicity of the solution
- Organization and clean code
- Utilization of components
- Mobile first & RWD
- Git usage
- Web Performance Optimization
- Technical knowledge
- Layout knowledge (HTML5 y CSS3)
