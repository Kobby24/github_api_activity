
# GitHub User Activity Tracker

---

## Overview
This script, **GitHub User Activity Tracker**, retrieves the most recent commit messages from a GitHub user's public activity using the GitHub API. It's a simple tool to track the latest actions of a GitHub user.

---

## Features
- Fetches the latest three commit messages from a specified GitHub username.
- Handles API connection errors gracefully.

---

## Requirements
1. **Python Version**: Ensure Python 3.x is installed.
2. **Libraries**:
   - `urllib` (Standard Python Library)
   - `json` (Standard Python Library)

---

## How to Use
1. Save the script as a `.py` file, for example, `github_activity_tracker.py`.
2. Run the script using your Python interpreter:
   ```bash
   python github_activity_tracker.py
   ```
3. Follow the prompts:
   - Enter a valid GitHub username when prompted.
   - View the latest commit messages displayed in the terminal.

---

## Sample Output
```plaintext
Welcome to Github User Activity Tracker
Enter your username
octocat
- Fixed a bug in the API integration
- Updated README.md with new instructions
- Added logging functionality to the project
```

---

## Error Handling
- If the script encounters an issue (e.g., invalid username or network error), it prints:
  ```
  Sorry Try again Later
  ```

---

## Limitations
1. Requires the GitHub user to have recent public commits.
2. The script fetches only the first three commit messages from the user's recent activity.
3. Rate-limited by GitHub API's unauthenticated access constraints (up to 60 requests per hour).

---

## Future Enhancements
- Add support for authenticated API requests to handle higher request limits.
- Display more detailed information, such as the repository name or commit timestamp.
- Implement pagination for more extensive activity tracking.

---

## Author
Kobby24
project url : [https://roadmap.sh/projects/github-user-activity]
