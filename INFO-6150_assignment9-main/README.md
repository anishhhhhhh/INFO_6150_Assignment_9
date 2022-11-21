The login page verifies the password and email. A post request is sent to localhost:8000/users/login (route created in the assignment8 repo). If the credentials are accurate, the page reroutes to the homepage; otherwise, an alert is displayed.

A navbar, a reusable component, is present on the Home, About, Jobs, and Contact pages and is used to switch between them.

To display content appropriately on all pages, a card component with the three props header, description, and isShowButton is reused.

A list of open positions is displayed on the jobs page using a map function.

The card component's button is dynamically rendered.
