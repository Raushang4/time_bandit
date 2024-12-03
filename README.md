# Time Bandit

Time Bandit is a command line time management application that lets you create `tasks` and log `events` for those tasks.

To install, use: `cargo install time_bandit` from crates.io.

With this app, you can track the total time spent on each task and view all associated events, including their duration and timestamps.

When you run the app for the first time, an SQLite database will be created at `~/.time_bandit.db3`.

Example usage:

`$ tb task start <task name> -details 'optional task description'`

This command starts a new task or resumes an existing one. For new tasks, the details provide a description. For subsequent events, `-details` adds notes to those events.

`$ tb task list`

This command lists all tasks along with the total time spent on each.

`$ tb events <optional task name>`

This command lists all events, showing their associated task, timestamp, duration, and any details.

# Update credentials for HTTPS

