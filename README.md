# Task - "contractrender"

Robin AI's product suite will include interfaces for viewing, labelling and editing contracts.

We require the ability to interact with text on a per-sentence basis. Contract objects are stored
in a backend service, which exposes an API. `src/api.ts` includes sample data to be used in this task - you
may use the `contract` object directly.

To complete this task, implement the following features:

1. The contract's text is clear and readable.
2. While hovering on text, the surrounding sentence should be highlighted in blue.
3. The user can select a single sentence on click, or multiple sentences on ctrl-click. 
   The selected sentence(s) should be highlighted in red.
4. The user can click a button to clear their selection. The button should be disabled if
   no sentences are selected.

Don't worry if you do not finish implementing all functionality in 40 minutes - the quality of the code you write 
is more important than whether the task has been completed. If you do finish, feel free to write some tests to verify 
the functionality.

**Note:** you may use Typescript or Javascript.

## Available Scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). 
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.
