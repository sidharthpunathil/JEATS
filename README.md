
# CS50w Final Project

## E2E Restaurant Application for the Pandemic Revival

- **RECENT** Made the application deployment ready. Find the app at https://res-manage.herokuapp.com/ or in active environments in the side (deployed to heroku from this repo)
- Any pushes made to this repository will be automatically deployed
- For a non-deployment locally runnable application revert to the previous version before the "Made application deployment ready (for Heroku)" commit (7a5639fd9...)
- Find demo at https://drive.google.com/file/d/1j3e9nErrwhi0EsqoeaVJgUbKzpdRTLUB/view?usp=sharing
- The website implements an E2E restaurant application that takes care of all the requirements of a restaurant with minimal staff which could help reduce contact during this current pandemic situation.
- The customer creates an account and then logs in and requests for a reservation. The manager can select from the available tables that are free in that slot which can seat the number of people required by the customer.
- If there is no such table available, the manager will decline the reservation.
- Once the manager accepts the reservation, the customer can confirm that he is at the restaurant. The manager can confirm this and the user can start ordering.
- The customer can now add items to the cart and place the order. After placing the order, the customer can see the live status of the order and see the preparation and delivery of the item.
- After customer has ordered the items, he can pay the final bill which the manager/waiter will bring to him/her.
- The manager confirms the payment and updates the status.
- The customer can then give feedback about the restaurant experience which the manager can then see in the feedback panel.
- Menu items and tables can be added from the Django Admin Panel
