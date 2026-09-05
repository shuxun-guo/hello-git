# Issue tracker: GitHub

Issues and specs live in GitHub Issues for `shuxun-guo/hello-git`.
Use the `gh` CLI from this repository.

## Conventions

- Create: `gh issue create --title "..." --body-file <path>`
- Read: `gh issue view <number> --comments`
- List: `gh issue list --state open --json number,title,body,labels`
- Comment: `gh issue comment <number> --body-file <path>`
- Add labels: `gh issue edit <number> --add-label "..."`
- Remove labels: `gh issue edit <number> --remove-label "..."`
- Close: `gh issue close <number> --comment "..."`

For multiline bodies, write the exact text to a temporary file and
pass it with `--body-file`.

Infer the repository from the Git remote. When necessary, specify
`--repo shuxun-guo/hello-git`.

## Pull requests as a triage surface

PRs as a request surface: no.

## Skill terminology

“Publish to the issue tracker” means create a GitHub issue.
“Fetch the relevant ticket” means read the issue and its comments.
