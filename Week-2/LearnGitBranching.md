# LearnGitBranching Writeups

## Introduction Sequence
1. Introduction to Git Commits
	1. git commit
	2. git commit

2. Branching in Git
	1. git branch bugFix
	2. git checkout bugFix
	3. OR Use git branch -b bugFix to merge above two commands

3. Merging in Git
	1. git branch bugFix
	2. git checkout bugFix
	3. git commit
	4. git checkout main
	5. git commit
	6. git merge bugFix

4. Rebase Introduction
	1. git checkout -b bugFix
	2. git commit
	3. git checkout main
	4. git commit
	5. git checkout bugFix
	6. git rebase main

## Ramping Up
1. Detach yo' HEAD
	1. git checkout C4

2. Relative Refs (^)
	1. git checkout bugFix^

3. Relative Refs #2 (~)
	1. git branch -f main C6
	2. git checkout HEAD~1
	3. git branch -f bugFix HEAD~1

4. Reversing Changes in Git
	1. git reset HEAD~1
	2. git checkout pushed
	3. git revert HEAD

## Moving Work Around
1. Cherry-pick Intro
	1. git cherry-pick c3 c4 c7

2. Interactive Rebase Intro
	1. git rebase -i HEAD~4
 
## A Mixed Bag
1. Grabbing Just 1 Commit
	1. git checkout main
	2. git cherry-pick c4
2. Juggling Commits
	1.  
