# Hospital Management Pro

React + Express + MySQL hospital management system.

## Features

- Overview panel with active patients, today's appointments by status, monthly revenue, and low-stock medicines.
- Appointment table with pagination, sorting, status badges, inline status update, and patient search.
- Revenue report chart with monthly invoice vs paid values and a date range picker that calls `/api/reports/revenue`.
- Book appointment form with patient, doctor, date/time selection and clear conflict errors from the API.
- Loading spinners, empty states, and disabled submit/status buttons while requests are running.

## Installation

1. Install Node.js and MySQL.
2. Create a database by running `database/schema.sql` in MySQL.
3. Copy `.env.example` to `.env` and update the database password if needed.
4. Open a terminal in this folder.
5. Run:

```bash
npm install
npm run start
```

If PowerShell blocks `npm`, use:

```bash
npm.cmd install
npm.cmd run start
```

Then open:

```text
http://localhost:5173
```

The API runs at:

```text
http://localhost:5000
```
