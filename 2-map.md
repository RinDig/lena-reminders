# Map: Lena's reminders (made-up example)

## What is here
- `1-stuff/clients.csv`: one row per client, 40 in all.
- `1-stuff/reminder-email-1.md` to `3`: Lena's own reminder emails from last year. Use them for her tone.

## How things are named
Clients by `client_id`, such as C014. The emails are numbered 1 to 3.

## What the numbers mean
- `sent_last_year`: the documents each client sent last year, separated by semicolons.
- `received_this_year`: what has come in so far. A blank means not checked yet. `none` means checked and nothing came.
- `notes`: anything Lena wants you to know about the client.

## What lives somewhere else, and how to get it
The full client record is in the practice software. `clients.csv` is a read-only export of it, refreshed by Lena.

## What must never be read, shared or changed
Nothing is ever sent. A note that says "ask Lena" means stop and ask her about that client.
