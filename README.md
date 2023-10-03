# Messages List Assignment 

![task](https://github.com/WaleedOmar87/senior-frontend-task/blob/main/design.png)
## Description 
The goal is to implement messages box where client can view and filter their social media accounts messages.

1. Client should be able to view and filter latest messages from multiple social media accounts.
2. Client should be able to filter messages based on tags, date and platform (facebook, twitter ..etc). 
3. Messages with `replied_to` property should have a green border around them according to the design. 
4. Implement the following design [Figma](https://www.figma.com/file/iX9aac3t8rCi3obf3pScJb/Dashboard-Design?type=design&node-id=0-1&mode=design&t=2GnliSu40rj0X16B-0)

## API 
1. You can use the provided data `data.json`

## Ideation
### All of the following points are mandatory.
1. A Loading screen is expected while fetching the data from the json file.
2. Implementation that matches the provided design.
4. Use any API Access Layer to store and cache the data, and mutate the data when the user changes category.
`RTK Query is preferred, but you can also use React Query or any other alternative that you're familiar with`.
5. Use React
6. Implement an `Error Boundaries` pattern to catch and display a user-friendly error message if there's an error in your code.
7. Don't use axios or fetch, rely on an API Access Layer such as RTK Query, React Query or a suitable alternative.
8. Use functional components instead of class based components.
9. Implement suitable design patterns, follow SOLID principles, Separation of concerns is required, So please separate view from business logic, Create modular and reusable components.
10. Follow flux guidelines when it comes to state management and data flow.

## Requirements 
### Note: 100% completion is not required, But make sure to finish at least the first 4 requirements.
1. Sort menu is expected to contain `tag` , `platform`, `status`, `replied_to`.
- When the user clicks on any of the above, messages should be sorted accordingly.
2. Message box should display message user name, message text, tag and sentiment status according to the design.
3. Search box is expected to be functional, 
- When the user click on the search box a dropdown menu should appear and display search options, Where the user can choose to search by message's user name or message content.
- When the client type a string the search box dropdown should display search results from messages.
4. Functional pagination section is expected at the bottom


## Bonus 
1. Typescript is a big bonus.
2. Implement Unit Tests using jest and React testing library
3. Implement E2E test using Cypress or Playwrite.

