# Spotfire Kanban Board Visualisation

Spotfire mods visualisation for Kanban board in Spotfire.

## To Do's

- Click on header to mark cards in column
- Sort cards alphabetically per column
- Add configure button for order of columns and default columns
- Use https://popper.js.org for configure dialog
- Render hierarchy with tree for headers using SVG like in prototype 
- Catch error if no column or card is defined by user
- New test data with more data and multiple colors per column
- Ellipsis or line break as an option to configure

## How to get started (with development server)
All source code for the mod example can be found in the `src` folder. 
These instructions assume that you have [Node.js](https://nodejs.org/en/) (which includes npm) installed.

- Open a terminal at the location of this example.
- Run `npm install`. This will install necessary tools. Run this command only the first time you are building the mod and skip this step for any subsequent builds.
- Run `npm run server`. This will start a development server.
- Start editing, for example `src/main.js`.
- In Spotfire, follow the steps of creating a new mod and connecting to the development server.
