# Far Away — Travel Packing List

**React learning path — Project 3.** Forms, lifting state up, child-to-parent communication.

"Far Away": a packing list for a trip. You add items with a quantity through a form and delete them from the list.

## Status

🚧 Unfinished: items can be added and deleted; the "packed" toggle and the stats footer are still placeholders.

## What I practiced

- Controlled form with `onSubmit` and `preventDefault`
- Generating `<option>` elements with `Array.from`
- Lifting state up to the parent component
- Passing handler functions as props (child-to-parent communication)
- Updating arrays in state immutably (spread and `filter`)

## Run it locally

Requires [Node.js](https://nodejs.org/) (LTS).

```bash
npm install
npm start
```

Then open http://localhost:3000.

## Built with

React 18 · Create React App (`react-scripts` 5)

## Part of a series

These repositories are exercises from my React learning path (2024), based on Jonas Schmedtmann's *The Ultimate React Course*.

| # | Repository | Topic |
|---|---|---|
| Project 1 | [Pizza Menu](https://github.com/stgermanrobert/React-Project-001---Pizza-Menu) | Components, props, rendering lists, conditional rendering |
| Challenge 1 | [Profile Card](https://github.com/stgermanrobert/React-Challenge-001---Profile-Card) | Components and props with a data list |
| Project 2 | [Flashcards](https://github.com/stgermanrobert/React-Project-002---Flashcards) | State with useState, click events |
| Challenge 3 | [Date Counter v2](https://github.com/stgermanrobert/React-Challenge-003---Day-Counter-v2) | Controlled inputs and derived state |
| Project 3 | **Far Away — Travel Packing List** (this repo) | Forms, lifting state up, child-to-parent communication |
