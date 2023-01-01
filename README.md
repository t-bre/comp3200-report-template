# COMP3200 Overleaf Report Template

## About
- This is an Overleaf project template for COMP3200 Part III Individual Project reports at the University of Southampton.
- It contains a minimal example project which you can import into Overleaf.
- Hopefully this will save you time in getting things set up with Overleaf, especially if LaTeX is new to you.
- You will need the LaTeX class file `ecsproject.cls` provided by ECS (see instructions below).
- You can reorganise files, folders and their contents as you like - this is just a minimal example as a starting point.
- Use at your own risk!

## Getting Started

If you want to put your report under version control using GitHub:
1. Create a new repo using this one as a template.
2. Log in to [Overleaf](https://www.overleaf.com/).
3. Link your GitHub to Overleaf under "Integrations" in your account settings.
4. Return to your projects on Overleaf and click "New Project."
5. Import the project from your fork of this repository ("Import from GitHub").
6. Provide the contents of `ecsproject.cls`.

If you just want to use Overleaf without version control:
1. [Download the files in this repo](https://github.com/t-bre/comp3200-report-template/archive/refs/heads/main.zip).
2. Log in to [Overleaf](https://www.overleaf.com/).
3. Return to your projects on Overleaf and click "New Project".
4. Import the project from the downloaded files ("Upload Project").
5. Provide the contents of `ecsproject.cls`.

## :warning: `ecsproject.cls` and `lstpatch.sty`
This file is required and should contain the `ecsproject` class created by Steve Gunn, which is copyrighted and has therefore not been included in this repository. 
The file is available for ECS students [on the intranet](https://secure.ecs.soton.ac.uk/notes/TeX/) - download `ecsdocs.zip`, find the file `ecsproject.cls` and replace the contents of the placeholder file with its actual contents. The contents of this file *must* be provided for the template to work! You will also need to either add `lstpatch.sty` to the root folder or remove the line in `ecsproject.cls` with `\usepackage{lstpatch}` (removing this may or may not cause problems depending on your use of the `listings` package).

> I submitted my final report in 2020/21, and this setup worked for me at the time.
> I have no intention to update this repo in future, but I thought it might be useful to someone.
