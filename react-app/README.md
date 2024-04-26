<h1 align="center">Client Side Pagination</h1>

Let us suppose that you are building a Pokémon client app that would use our Pokémon API server to get the data.

The client app will fetch all the Pokémons and paginate the Pokémons to a user. For example, you may choose to display 10 Pokémons at a time and allow the user to navigate back and forth using `next` and `prev` buttons. Or even better, choose a page number.

This means that instead of displaying all 809 Pokémons, you could have 81 pages with each page showing 10 records.

Here’s what the app looks like with pagination.

## Additional Requirements

- Show only 10 pages at a time
- For each page, display the Pokémon in a responsive grid.
- Hide the `prev` and `next` buttons if you are at the first or last pages, respectively.
- Using CSS, highlight the selected page in the pagination controls.


