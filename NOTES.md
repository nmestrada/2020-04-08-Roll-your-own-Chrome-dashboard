This article was very helpful to get this working!!!!

https://medium.com/@gilfink/building-a-chrome-extension-using-react-c5bfe45aaf36

## Installation
`npx create-react-app yourAppName`

`npm install`

customize your code 

`npm build`

comes with a lot of boilerplate code

then set your chrome extension on the build folder

it was important to add this to the npm run build script --> INLINE_RUNTIME_CHUNK=false, because Chrome banned inline scripts? 