# Latex Template

Made by Fabian Tilmans

This Visual Studio Latex template guaratees an clean and good looking content. 

## Requirements

A way to build Latex files. Thats it.
If you use Overleaf or similar technologies, simply copy the Config/config.tex and paste it into your own latex file.

## Usage

The Main.tex file is the main entry point of the build. To change the document type, find the ``` documentclass[]{[document type here]}``` command and change the type for your needs (standard is article).

Images a stored under ``` Assets/Images ``` the default image path is configured in the config.tex. Therefore, if you want du include an image use the ``` includegraphics{[Filename here]}``` and paste the filename into the braclets.

If there is anything you dont need in you article/thesis, simply comment it out. If there should be any bugs or warnings, inform me via github.