# Power BI Project: Booking Analysis Dashboard

## 📖 Overview
Providing a comprehensive view of booking analysis and visualization for National Rail in the UK, helping track purchase trends, analyze Railcard usage, and identify refund patterns.

![Booking Analysis Dashboard](screenshots/booking_dashboard.png)

## 📁 Data Model

→ `railway_booking.csv` 

| Column               | Type        | Description                                |
|----------------------|------------|--------------------------------------------|
| Transaction ID       | text       | Unique identifier for each purchase        |
| Date of Purchase     | date       | Date when the ticket was purchased         |
| Time of Purchase     | time       | Time when the ticket was purchased         |
| Purchase Type        | text       | Type of purchase (online, counter, app)   |
| Payment Method       | text       | Method used for payment (card, cash, etc.)|
| Railcard             | text       | Railcard used, if any                      |
| Ticket Class         | text       | Class of the ticket (Standard, First)     |
| Ticket Type          | text       | Type of ticket (Single, Return, Season)   |
| Price                | float      | Price paid for the ticket                  |
| Departure Station    | text       | Station from which the journey started    |
| Arrival Destination  | text       | Station where the journey ended            |
| Date of Journey      | date       | Scheduled date of travel                   |
| Departure Time       | time       | Scheduled departure time                   |
| Arrival Time         | time       | Scheduled arrival time                     |
| Actual Arrival Time  | time       | Real arrival time                           |
| Journey Status       | text       | Status of the journey (On time, Delayed)  |
| Reason for Delay     | text       | Reason for delay, if any                   |
| Refund Request       | boolean    | Whether a refund was requested             |

## 📊 Dashboard 

#### KPIs (Bookings Report - March 2024)
1. **Bookings:** 194.8K (+2.4% MoM).
2. **Revenue:** £261K (+15% MoM).
3. **Average Daily Bookings:** 10.5K (+2.4% MoM).
4. **Lost Revenue:** £10.5K (+24% MoM).
5. **On-Time Journeys:** 85.9% (-1.2pts MoM).

#### KPIs (Usage Report - March 2024)
1. **Bookings on Weekends (%):** 46.3% (-2.4pts MoM)
2. **Bookings on Weekends (%):**  53.7% (-2.4pts MoM).
3. **Average Advance Purchase:** 1 day (-4 days MoM).
4. **Average ticket price:** £24 (+12.3pts MoM)
5. **Online purchase (%):** 58.0% (-1.6pts MoM)

