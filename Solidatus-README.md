# 2023-05-03

Created as

- Currently we have 4 High CVEs from the bundled monstache gobinary @ `6.7.7`
- By updating to `6.7.10` we get down to 2. This version should work fine, I have used it a bit in past when looking at a different issue where I thought monstache update may help
- By updating to `6.7.11` (latest at time of writing) we get down to 1 CVE left. HOWEVER, this version has bug that breaks our sync. I commented about this on GH mid last month, had no response, no fix :disappointed:

SO:

- added branch `v6.7.10.x`
- cherry-picked all commits from `rel6` that update Mongo driver or other dependencies. This fixes all CVEs
- Updated version to `6.7.10.0` in `monstache.go`
- Created new release by using new `./build.sh` script

# 2023-06-20

Golang has 3 vulnerabilities CVE-2023-24540, CVE-2023-29400, CVE-2023-24539 which were fixed in 1.20.4 hence manually updated go.mod to use 1.20. (latest on main branch was 1.19)

# 2023-08-24

Golang has 3 vulnerabilities CVE-2023-29409, CVE-2023-29406, CVE-2023-39533 which were fixed in 1.20.7 hence manually updated go.mod to use 1.21. (latest on main branch was 1.20)

# 2023-10-18

Golang has 1 vulnerability CVE-2023-39320 which was fixed in 1.21.3 hence manually updated go.mod to use 1.21.3. (latest on main branch was 1.21)

# 2024-01-10

Golang has 2 vulnerability CVE-2023-39326 and CVE-2023-45285 which was fixed in 1.21.6 hence manually updated go.mod to use 1.21.6. (latest on main branch was 1.21.3)

# 2024-05-07

Golang has 1 vulnerability CVE-2023-48795 which was fixed in golang.org/x/crypto v0.17.0.The versions of golang.org/x/text v0.14.0 and golang.org/x/sys v0.15.0 bumped as related packages for golang.org/x/crypto v0.17.0.

# 2024-06-20

Golang has 2 vulnerability CVE-2024-24790 and CVE-2024-24789 which was fixed in 1.21.11 hence manually updated go.mod to use 1.21.11. (latest on main branch was 1.21.6)

# 2024-10-18

Golang has 4 vulnerability CVE-2024-34156, CVE-2024-34158, CVE-2024-34155 and CVE-2024-24791 which was fixed in 1.23.1 hence manually updated go.mod to use 1.23.1 (latest on main branch was 1.21.11)

# 2024-12-16

Golang has 1 vulnerability CVE-2024-45337 which was fixed in golang.org/x/crypto v0.31.0.The versions of golang.org/x/text v0.21.0, golang.org/x/sync v0.10.0 and golang.org/x/sys v0.28.0 bumped as related packages for golang.org/x/crypto v0.31.0.

# 2025-01-30

Golang has 2 vulnerabilities CVE-2024-45336, CVE-2024-45341 which was fixed in 1.23.5 hence manually updated go.mod to use 1.23.5.(latest on main branch was 1.23.1)

# 2025-02-24

Golang has 1 vulnerability CVE-2025-22866 which was fixed in 1.23.6 hence manually updated go.mod to use 1.23.6.(latest on main branch was 1.23.5)

# 2025-04-28

Golang has 1 vulnerability CVE-2025-22869 which was fixed in golang.org/x/crypto v0.35.0.The versions of golang.org/x/text v0.22.0, golang.org/x/sync v0.11.0 and golang.org/x/sys v0.30.0 bumped as related packages for golang.org/x/crypto v0.35.0.

# 2025-04-28

Golang has 1 vulnerability CVE-2025-22871 which was fixed in 1.23.8 hence manually updated go.mod to use 1.23.8.(latest on main branch was 1.23.6)

# 2025-06-20

Golang has 3 vulnerabilities CVE-2025-22874, CVE-2025-4673 and CVE-2025-0913. CVE-2025-22874 was addressed by upgrading the following dependencies: golang.org/x/crypto to v0.39.0, golang.org/x/net to v0.41.0, golang.org/x/sync to v0.15.0, golang.org/x/sys to v0.33.0 and golang.org/x/text to v0.26.0. The remaining two were fixed in 1.24.4 hence manually updated go.mod to use 1.24.4 (latest on main branch was 1.23.8)

# 2025-08-20

Golang has 1 vulnerability CVE-2025-47907 which was fixed in 1.24.6 hence manually updated go.mod to use 1.24.6.(latest on main branch was 1.24.4)

# 2025-11-04

Golang has 10 vulnerability CVE-2025-61725, CVE-2025-61723, CVE-2025-58189, CVE-2025-58185, CVE-2025-61724, CVE-2025-58188, CVE-2025-58187,  CVE-2025-58186,  CVE-2025-58183,  CVE-2025-47912,  CVE-2025-61725,  CVE-2025-61723,  CVE-2025-58189 and CVE-2025-58185 which was fixed in 1.24.9 hence manually updated go.mod to use 1.24.9.(latest on main branch was 1.24.6)

# 2025-12-10

Golang has 12 vulnerabilities CVE-2025-58183, CVE-2025-58186, CVE-2025-58187, CVE-2025-61729, CVE-2025-47912, CVE-2025-58185, CVE-2025-58188, CVE-2025-58189, CVE-2025-61723, CVE-2025-61724, CVE-2025-61725 and CVE-2025-61727 which was fixed in 1.24.11 hence manually updated go.mod to use 1.24.11.(latest on main branch was 1.24.9)

# 2025-12-10

Golang has 2 vulnerability CVE-2025-47914 and CVE-2025-58181 which was fixed in golang.org/x/crypto v0.45.0.The versions of golang.org/x/text v0.31.0, golang.org/x/sync v0.18.0 and golang.org/x/sys v0.38.0 bumped as related packages for golang.org/x/crypto v0.45.0.

# 2026-01-30
Golang has 3 vulnerability CVE-2025-61730, CVE-2025-61728, CVE-2025-61726 which was fixed in 1.24.12 hence manually updated go.mod to use 1.24.12.(latest on main branch was 1.24.11)

# 2026-02-06
Golang has 2 vulnerability CVE-2025-61732, CVE-2025-68121 which was fixed in 1.25.7 hence manually updated go.mod to use 1.25.7.(latest on main branch was 1.24.12)

# 2026-03-09
Golang has 5 vulnerability CVE-2026-27142, CVE-2026-27139, CVE-2026-27138, CVE-2026-27137 and CVE-2026-25679 which was fixed in 1.26.1 hence manually updated go.mod to use 1.26.1.(latest on main branch was 1.25.7)

# 2026-04-08
Golang has 7 vulnerabilities CVE-2026-33810, CVE-2026-32289, CVE-2026-32288, CVE-2026-32283, CVE-2026-32282, CVE-2026-32281 and CVE-2026-32280 which are fixed in 1.26.2 hence manually updated go.mod to use 1.26.2. (latest on main branch is 1.26.1)

# 2026-05-12

Golang has 11 vulnerabilities CVE-2026-42501, CVE-2026-42499, CVE-2026-39836, CVE-2026-39820, CVE-2026-33814, CVE-2026-33811, CVE-2026-39826, CVE-2026-39825, CVE-2026-39823, CVE-2026-39819 and CVE-2026-39817 which were fixed in 1.26.3 hence manually updated go.mod to use 1.26.3. (latest on main branch was 1.26.2)

# 2026-06-04

Golang has 3 vulnerabilities CVE-2026-42507, CVE-2026-42504 and CVE-2026-27145 which were fixed in 1.26.4 hence manually updated go.mod to use 1.26.4. (latest on main branch was 1.26.3)

# 2026-06-23

Golang has 15 vulnerabilities CVE-2026-46597, CVE-2026-46595, CVE-2026-42508, CVE-2026-39835, CVE-2026-39830, CVE-2026-39829, CVE-2026-39828, CVE-2026-39827, CVE-2026-46598
CVE-2026-39834, CVE-2026-39833, CVE-2026-39832, CVE-2026-39831, CVE-2026-2303 and CVE-2026-39824 which were addressed by upgrading golang.org/x/crypto to v0.52.0 and golang.org/x/sys to v0.45.0. The versions of golang.org/x/net v0.54.0, golang.org/x/sync v0.20.0 and golang.org/x/text v0.37.0 were bumped as related packages for golang.org/x/crypto v0.52.0.

# 2026-07-20
Golang has 2 vulnerabilities CVE-2026-42505, CVE-2026-39822 which were fixed in 1.26.5, hence manually updated go.mod to use 1.26.5 (latest on main branch was 1.26.4).

# 2026-07-23
MongoDB Go driver has 1 vulnerability CVE-2026-2303 which was fixed by upgrading go.mongodb.org/mongo-driver to v1.17.7, hence updated go.mod and go.sum to use go.mongodb.org/mongo-driver v1.17.7 (latest on main branch was v1.11.4). The version of github.com/rwynn/gtm/v2 was bumped to v2.1.5 as a related package for go.mongodb.org/mongo-driver v1.17.7.
