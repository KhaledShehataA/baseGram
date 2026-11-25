# BaseGram

A photo gallery app in the style of Instagram, built with React. This is an early-stage learning project (started August 2020). Right now it only has the page header ("BaseGram - Your Pictures"). Firebase upload and the gallery are not implemented yet.

## Tech stack
- React 16.13
- react-scripts (Create React App) 3.4.1
- Jest and React Testing Library (included by the CRA template)

## Requirements
- Node.js and npm

## Install and run
```bash
git clone https://github.com/KhaledShehataA/baseGram.git
cd baseGram
npm install
npm start
```
The app opens at http://localhost:3000.

## Environment variables
None are needed at the moment. When Firebase is added, its keys will go in a local `.env` file that is not committed.

## Usage
Currently the app shows the title component only (`src/comps/Title.js`).

## Screenshots / demo
Not available yet.

## Tests
```bash
npm test
```
No custom tests have been written yet.

## Roadmap
- Image upload with Firebase storage
- Gallery grid of uploaded pictures
