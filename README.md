# SBratio

## Intoduction

This project is to calculate the signal-background ratio of microscope image. The programming language is C#, because its speed is better than Python if the image is too large.

## How to use

We could download the directory bin/Debug/net5.0/. There are test file which is processed by ImageJ. One is for signal (ClearOutside.tif), and another is for backgorund.
Click the SBratio.exe (You need to make sure that you have .net core in your computer) and enter the directory name (test). It will output txt file. First column of txt file is signal and second is background. And then you could use python or matlab to analyze it.
