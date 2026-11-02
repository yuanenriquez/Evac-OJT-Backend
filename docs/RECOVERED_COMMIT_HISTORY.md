# Recovered 2024 Git commit history

This table maps the six commits from my original private `Evac` repository to the sanitized public commits in this repository.

I recovered the original history from my private `yuanenriquez/Evac` repository and the `Evac.zip` archive. For this public copy, I kept my author name **Yuan Haley Enriquez**, the original author/committer dates, commit messages, chronological sequence, and source snapshots. I replaced my university email with my GitHub-provided `noreply` address and redacted the OAuth credential in the August 5 source snapshot.

Because Git commit IDs hash the commit metadata and content, **all six public commit hashes differ from their private originals** after these privacy/security changes. This is expected. I left my original private repository unchanged.

| Original private short SHA | Sanitized public short SHA | Original date (PHT) | Original commit message |
|---|---|---|---|
| `1aac832` | `9eb9f27` | 2024-08-01 | `FIrst commit, working database` |
| `4fd151a` | `c16477b` | 2024-08-01 | `space only` |
| `8f13708` | `3cca528` | 2024-08-04 | `added gitignore` |
| `6eb3cf6` | `dc6a293` | 2024-08-04 | `updated gitignore` |
| `4b63cad` | `dd2efb0` | 2024-08-05 | `add client ID and client secret` |
| `b3b2288` | `8e398be` | 2024-08-13 | `first commit` |

## What the history supports

The first commit contains the Express server, Sequelize/MySQL setup, User model, registration/login routes, and project files. Subsequent commits include the experimental Passport/Google OAuth code, dependency/configuration changes, `.gitignore` updates, the OAuth configuration change, and a README addition.

The Git author metadata supports the development timeline for my backend work. Because this was a collaborative academic project, I describe my backend contribution without claiming that I built the entire application.

## Separate stash

My recovered private archive also contains a Git stash from August 1, 2024. It is work-in-progress state, not an additional ordinary commit on `main`, so I did not include it in the six-commit public history.
