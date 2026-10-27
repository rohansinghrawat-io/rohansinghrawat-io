Backend engineer at [Instantpay](https://www.instantpay.in). New Delhi.

I build Laravel APIs for a live rally and treasure-hunt platform. Organizers set the course, marshals run checkpoints, riders stay on the map, and the results, credits, and payments have to match what happened on the ground.

| | |
| --- | --- |
| **APIs** | PHP 8 and Laravel. One response contract. JWT sessions. A route group for each role: owner, organizer, manager, staff, marshal, rider. |
| **Data** | MySQL holds the record. Redis holds live GPS. Queues take the work that should not sit inside the request. |
| **Realtime** | A Node WebSocket service runs beside the API for live tracking and SOS. |
| **Money** | Razorpay and PayPal, and the credit ledger organizers spend from. |
| **Consoles** | Next.js and TypeScript for the owner and organizer panels. Older AngularJS screens move when that workflow is ready. |
| **Shape of the code** | Thin controllers. Rules in services. Validation and status codes in one place. Docs change in the same commit as the behavior. |

`PHP` · `Laravel` · `MySQL` · `Redis` · `Node` · `Next.js` · `TypeScript` · `Docker`

[LinkedIn](https://www.linkedin.com/in/rohan-singh-918174191)
