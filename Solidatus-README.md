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