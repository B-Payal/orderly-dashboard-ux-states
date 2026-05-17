## Overview
The original Orders Dashboard fetched data but did not clearly communicate its state to users. It often showed a blank screen or unclear output, making it difficult to know whether data was loading, empty, or if an error had occurred.

To improve the user experience, I implemented all four essential UX states: **Loading, Success, Empty, and Error**.

## Issues Identified
- No loading indicator while fetching data
- Order data was not displayed clearly
- No message when no orders were available
- No proper error handling or recovery option

## Improvements Made

### Loading State
Added skeleton loading rows to show users that data is being fetched.

### Success State
Displayed orders in a structured table with:
- Order ID
- Customer Name
- Order Date
- Total Amount
- Status
- Priority Flag

Also added summary metrics:
- Total Orders
- Total Order Value
- Status Breakdown

### Empty State
Added clear messages when:
- No orders are available
- No orders match active filters

### Error State
Added specific error messages with a **Retry** button to help users recover quickly.

## Impact
These improvements make the dashboard more user-friendly, reduce confusion, and help users understand exactly what is happening at every stage.

## Deployment URL
https://orderly-dashboard-ux-states-five.vercel.app/

