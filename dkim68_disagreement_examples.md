# Disagreement Examples — dkim68 & eabbott9

These are six examples from our discussion. Three kept my validation and three kept eabbott9's original value.

## Example 1 — daducci_amico (Currentstatus)
**Author (eabbott9):** False  
**Validator (dkim68):** True  
**Adjudicated Value:** True  
**Resolution:** dkim68 (ValidatorKept)  
**Reason:** The coding guide uses a fixed cutoff. The last commit is after 2025-04-01, so the project is Active.

## Example 2 — scikit-fuzzy_scikit-fuzzy (RecentThemes)
**Author (eabbott9):** ['bug', 'release']  
**Validator (dkim68):** ['bug', 'build']  
**Adjudicated Value:** ['bug', 'release']  
**Resolution:** eabbott9 (AuthorKept)  
**Reason:** There are several FIX commits and an explicit RELEASE: Version 0.5.0 commit. There is build work too, but release is directly stated.

## Example 3 — anybotics_kindr (ActivityPattern)
**Author (eabbott9):** steady  
**Validator (dkim68):** declining  
**Adjudicated Value:** declining  
**Resolution:** dkim68 (ValidatorKept)  
**Reason:** The early years are much more active than the later years. The overall direction is down.

## Example 4 — cmillion_gphoton (RecentThemes)
**Author (eabbott9):** ['documentation', 'feature']  
**Validator (dkim68):** ['documentation', 'build']  
**Adjudicated Value:** ['documentation', 'feature']  
**Resolution:** eabbott9 (AuthorKept)  
**Reason:** Recent commits include README/install documentation and experimental PhotonPipe updates, so feature is supported.

## Example 5 — aim-uofa_adelaidet (RecentThemes)
**Author (eabbott9):** ['feature', 'documentation']  
**Validator (dkim68):** ['documentation', 'bug']  
**Adjudicated Value:** ['documentation', 'bug']  
**Resolution:** dkim68 (ValidatorKept)  
**Reason:** The recent non-merge commits are mostly documentation/model-link changes plus a bug fix.

## Example 6 — daducci_amico (WhyRecovered)
**Author (eabbott9):** Several pull requests were merged, suggesting slow work was being performed and submitted all at once.  
**Validator (dkim68):** Work came back for bug fixes, version updates, and CI/build work.  
**Adjudicated Value:** Several pull requests were merged, suggesting slow work was being performed and submitted all at once.  
**Resolution:** eabbott9 (AuthorKept)  
**Reason:** Several merged PRs are clustered around the recovery. The fixes and build work describe what changed, but the PR cluster is a reasonable explanation for why activity returned.
