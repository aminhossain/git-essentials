<h1 align="center">Git Essentials</h1>
<p align="center">Frequently used git commands collection and git basics.</p>

## Introduction

<p>
This repository contains frequently used git commands with descriptions and uses.
</p>

## Contents

### GIT SETUP

> Configuring user information used across all local repositories

- set a name that is identifiable for credit when review version history\
  `git config --global user.name "[firstname lastname]"`

- set an email address that will be associated with each history marker\
  `git config --global user.email “[valid-email]”`

- set automatic command line coloring for Git for easy reviewing\
  `git config --global color.ui auto`

### SETUP & INIT

> Configuring user information, initializing and cloning repositories

- initialize an existing directory as a Git repository\
  `git init`

- retrieve an entire repository from a hosted location via URL\
  `git clone [url]`
