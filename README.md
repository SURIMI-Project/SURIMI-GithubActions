# Eii.GithubActions
A repo for CustomActions



## BuildCheckWindows
This is a custom action that builds the project using only the github-Surimi-project package source
It uses powershell (`pwsh`) to run the build script, and is designed to run on `windows-latest`.

## BuildCheckUbuntuBSR
This is a custom action that builds the project using both the github-Surimi-project and BSR package sources
It uses bash (`bash`) to run the build script, and is designed to run on `ubuntu-latest`.

## BuildCheckTestUbuntuBSR
This is a custom action that builds the project using both the github-Surimi-project and BSR package sources, and then runs all unit tests in the solution.
It uses bash (`bash`) to run the build and test scripts, and is designed to run on `ubuntu-latest`.
