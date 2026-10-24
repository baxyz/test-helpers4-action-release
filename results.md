| Cas | Résultat | Détail |
| --- | --- | --- |
| 1 · API, commit hors branche, parent = HEAD de main | OK | verified=true reason=valid author=github-actions[bot] committer=GitHub |
| 2 · API, parent = HEAD~1 de main, sur aucune branche (workflows différents) | FAIL: {"message":"Resource not accessible by integration","documentation_url":"https://docs.github.com/rest/git/refs#create-a-reference","status":"403"}gh: Resource not accessible by integration (HTTP 403) | - |
| 6a · API, nouvelle branche sur un commit existant (workflows différents de main) | OK | - |
| 6b · API, tag sur un commit existant (workflows différents de main) | OK | - |
| 7 · API, commit de release, parent = HEAD de la branche maint | OK | verified=true reason=valid author=github-actions[bot] committer=GitHub |
| 8 · API, fast-forward de maint vers le commit de release, puis tag | ff=OK tag=OK | - |
| 9 · API, parent = HEAD de main mais arbre = celui de maint | OK | - |
