# Task - "contractrender"

Robin AI's product suite will include interfaces for viewing, labelling and editing contracts.

We require the ability to interact with text on a per-sentence basis. Contract objects are stored
in a backend service, which exposes an API. `src/api.ts` includes sample data to be used in this task.
You can retrieve the contract by using the asynchronous function `getContract` or by accessing the `dataFromBackend` object directly.

## The Contract

The contract object contains some metadata about a contract - its name, id and an array of text blocks. Each text block represents a paragraph of text within the contract.
Each text block contains an array of sentence objects. Each object contains details of where sentences are located within it. The start and end values are indexes within the text string of the start and end of a sentence.

## Requirements

To complete this task, implement the following features:

1. Render the paragraphs of the contract in the browser so they are clear and readable.
2. While hovering on a paragraph, the paragraph should be highlighted in blue.
3. The user can select a single paragraph on click, or multiple paragraphs on ctrl-click.
   The selected paragraph(s) should be highlighted in red.
4. The user can click a button to clear their selection. The button should be disabled if no paragraphs are selected.

---

**_If you have completed the above_** - consider changing your implementation to support sentences using the sentence indice information in the contract object.
The requirements would now be:

5. While hovering on a sentence, the surrounding sentence should be highlighted in blue.
6. The user can select a single sentence on click, or multiple sentences on ctrl-click.
   The selected sentence(s) should be highlighted in red.
7. The user can click a button to clear their selection. The button should be disabled if
   no sentences are selected.

Don't worry if you do not finish implementing all functionality in 40 minutes - the quality of the code you write
is more important than whether the task has been completed. If you do finish, feel free to write some tests to verify
the functionality.

## Setting up the project

You are welcome to use whichever SPA framework you are most comfortable in.
We recommend setting up in the simplest way possible !

**Note:** you may use Typescript or Javascript.
