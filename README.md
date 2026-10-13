# LeetForces

My accepted solutions to [LeetCode](https://leetcode.com/u/asuf10ppy/) and [Codeforces](https://codeforces.com/profile/f10ppy) problems, pushed here automatically as I solve them.

## Profiles

| Platform | Handle | Link |
| --- | --- | --- |
| LeetCode | `asuf10ppy` | [leetcode.com/u/asuf10ppy](https://leetcode.com/u/asuf10ppy/) |
| Codeforces | `f10ppy` | [codeforces.com/profile/f10ppy](https://codeforces.com/profile/f10ppy) |

Current numbers are in [`stats.json`](stats.json), which is updated automatically whenever they change.

## Repository layout

```
LeetForces/
├── LeetCode/       # LeetCode solutions, one file per problem
├── Codeforces/     # Codeforces solutions, one file per problem
├── stats.json      # latest solved counts and rating
└── README.md
```

### File naming

- **LeetCode:** `Problem_Title.ext`, for example `Two_Sum.py`
- **Codeforces:** `<contest><index>_Problem_Name.ext`, for example `1850A_To_My_Critics.cpp`

If a problem is solved more than once, the file is overwritten with the latest accepted solution, and the full history stays in the commit log.

## How it works

Solutions are synced by a small personal Chrome extension (CodeSync Suite):

- **LeetCode:** when a submission shows *Accepted*, the code is committed to `LeetCode/`.
- **Codeforces:** new accepted submissions are checked every few minutes and committed to `Codeforces/`.
- **Stats:** solved counts and rating are refreshed hourly and written to `stats.json`.

Commit messages follow the pattern `Solved <Problem Name>`.

## Notes

- Solutions are for learning and practice. Try the problem yourself first.
- Older files may have a `.txt` extension from an earlier version of the sync tool.
