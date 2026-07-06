**The frontend price bug fix** - The total price on the Booking page was not updating because it lacked an event listener. I resolved this by adding an event listener to the end date input. Now, whenever I change the date it invoke the updateTotal() method to recalculate the totals and display the new total.

**The double-booking bug failure** - The original code wrongly allows booking of dates Jan 09 2026 - Jan 15 2026 event though the item was already booked for Jan 10 2026 – Jan 15 2026.

**How I use AI** - I use AI as a tool to help speed up debugging, brainstorm alternative implementations, help me understand unfamiliar code by breaking it down line by line, and refine my grammar. I verify that output is correct by manually testing the overlapping range logic using various combinations of conflicting dates.
