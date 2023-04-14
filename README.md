# minyr

Den største problemene under oppgaven var importering. Til nå, har jeg til nå satt opp kodene og filene på en midlertidig repository "testyr".

## Impotering av repository til koden:
Har prøvd å gjøre minyr-repository "public", men kommer med den samme error når man prøver å laste ned modulene (go mod init --> go mod tidy)

```bash
go: finding module for package github.com/StevenMTN/funtemps/conv
yr imports
        github.com/StevenMTN/funtemps/conv: cannot find module providing package github.com/StevenMTN/funtemps/conv: module github.com/StevenMTN/funtemps/conv: git ls-remote -q origin in C:\Users\Steven\go\pkg\mod\cache\vcs\0a12f19ec8465f1d197d16c9ef39730b3c4dd5987d0b0986e2d64e24cf345471: exit status 128:
        remote: Repository not found.
        fatal: repository 'https://github.com/StevenMTN/funtemps/' not found
```
På grunn av dette, har det ikke vært mulig å kjøre koden og instalert riktig go.mod og go.sum.