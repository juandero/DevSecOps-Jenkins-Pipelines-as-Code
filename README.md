# DevSecOps via Jenkins Pipelines & Configurations as Code

## Description

A repository that was born as a project to collect a wide variety of practice DevSecOps implementions via Jenkins Pipelines and Configurations as Code.

The main objective is to help anyone who needs to implement this kind of practices on their projects, taking these resources as basis for it.

> Please be sure to do not deploy this in production environments without before understand and adjust the implemented codes to your own needs. For sure, it could just break something!

## Currently working on

At this moment, work has been done on the development of some Pipelines as Code configurations that include SAST and SCA practices on Continuous Integration for Python projects. The next will be working on pipelines for Java projects, later for Javascript, and so on.

## Pipeline features

Some of the main features and capacities to be implemented for each type of pipeline-by-language are the following:
- To download the source code from parameterized git repository.
- To integrate at least five tools for SCA analysis.
- To integrate at least five tools for SAST analysis.
- To integrate at least three tools for secrets scanning.
- To parameterize a list of integrated tools that will be selected to be used when launching a Job.
- To store the tool reports as artifacts, on JSON format.
- To store summarized reports as artifacts, on CSV format.

## To-Do tasks (At the moment)

- [ ] Finish the Pipeline as Code for Python projects.
- [ ] Implement an auto-install method using JCasC to start a pre-configured server from scratch.
- [ ] Create and document a directory structure to store the codes.


## Disclaimer

All the implementations on this repository are entirely based on the exclusively use of Free/Open Source software. If a privative tool results implemented, it will be done based on its Free/Open version only.

## Contributing

Please feel free to look through the open issues, make a fork and submit a PR for improvements. All the suggestions, updates, fixes, new features and capabilities are appreciated.

Obviously, all contributors obtain copyrights on the project.

## Issues and Support

If you have suggestions, questions or issues running some codes, feel free to open an issue to contact and receive help.

At this moment no other channels (like e-mail or social media) are being used for support purposes. So please, do not try to contact me through other ways for this matter.

## Licence

- Code and documentation copyright (c) 2023-Present Juan P. Montero (A.k.a. [juandero](https://github.com/juandero)).
- Source code licensed under [MIT License](https://github.com/juandero/DevSecOps-Jenkins-Pipelines/blob/main/LICENSE).
- Documentation licensed under [Creative Commons Attribution 4.0 license](https://creativecommons.org/licenses/by/4.0/).