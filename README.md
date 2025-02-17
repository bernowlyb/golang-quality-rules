# Go Quality Rules Repository

Welcome to the **Go Quality Rules Repository**. This repository contains our Golang coding rules that are enforced in SonarQube to maintain high code quality and enhance developer productivity.

## Overview

Our SonarQube tool currently enforces **38 Golang rules**. Every issue identified in our Go projects results from non-compliance with one of these rules. Encouragingly, all current issues are concentrated in just **10 rules**, while the other **28 rules** show no occurrences. This repository is organized to reflect this insight.

## Repository Structure

The repository is divided into two main folders:

- **essential-rules**: Contains the 10 Golang rules that are currently generating issues. These are the critical rules where most of our code quality problems originate.
- **additional-rules**: Contains the remaining 28 Golang rules that currently have no reported issues.

## Essential Rules

Below is a summary of the 10 essential rules:

| **Code**   | **Description**                                                                 |
|------------|---------------------------------------------------------------------------------|
| go:S3776   | Cognitive Complexity of Functions Should Not Be Too High                        |
| go:S1192   | String Literals Should Not Be Duplicated                                        |
| go:S1135   | Track Uses of "TODO" Tags                                                       |
| go:S117    | Local Variable and Function Parameter Names Should Comply with a Naming Convention |
| go:S100    | Function Names Should Comply with a Naming Convention                           |
| go:S1763   | Functions Should Not Have Too Many Parameters                                   |
| go:S1871   | Two Branches in a Conditional Structure Should Not Have Exactly the Same Implementation |
| go:S4144   | Functions Should Not Have Identical Implementations                             |
| go:S1186   | Functions Should Not Be Empty                                                  |
| go:S1479   | "switch" Statements Should Not Have Too Many "case" Clauses                      |

