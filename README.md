# Go Quality Rules Repository

Welcome to the **Go Quality Rules Repository**. This repository contains our Golang coding rules that are enforced in SonarQube to maintain high code quality and enhance developer productivity.

## Overview

Our SonarQube tool currently enforces **38 Golang rules**. Every issue identified in our Go projects results from non-compliance with one of these rules. Encouragingly, all current issues are concentrated in just **10 rules**, while the other **28 rules** show no occurrences. This repository is organized to reflect this insight.

## Repository Structure

The repository is divided into two main folders:

- **essential-rules**: Contains the 10 Golang rules that are currently generating issues. These are the critical rules where most of our code quality problems originate.
- **additional-rules**: Contains the remaining 28 Golang rules that currently have no reported issues.

## Current Issue Breakdown

Below is a summary of the issues detected by SonarQube for the 10 essential rules (based on a total of 265 issues):

| **Code**   | **Description**                                                                 | **Issues** | **Percentage of Total Issues** |
|------------|---------------------------------------------------------------------------------|------------|--------------------------------|
| go:S3776   | Cognitive Complexity of Functions Should Not Be Too High                        | 81         | 30.57%                         |
| go:S1192   | String Literals Should Not Be Duplicated                                        | 78         | 29.43%                         |
| go:S1135   | Track Uses of "TODO" Tags                                                       | 43         | 16.23%                         |
| go:S117    | Local Variable and Function Parameter Names Should Comply with a Naming Convention | 39         | 14.72%                         |
| go:S100    | Function Names Should Comply with a Naming Convention                           | 9          | 3.40%                          |
| go:S1763   | Functions Should Not Have Too Many Parameters                                   | 5          | 1.89%                          |
| go:S1871   | Two Branches in a Conditional Structure Should Not Have Exactly the Same Implementation | 5   | 1.89%                          |
| go:S4144   | Functions Should Not Have Identical Implementations                             | 3          | 1.13%                          |
| go:S1186   | Functions Should Not Be Empty                                                  | 1          | 0.38%                          |
| go:S1479   | "switch" Statements Should Not Have Too Many "case" Clauses                      | 1          | 0.38%                          |

