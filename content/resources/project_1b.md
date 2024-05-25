---
title: "Project 1B: Developing a New Voltage Reporter"
date: 2024-05-24
draft: false
description: "The purpose of this project is to develop a method for optaining cell membrane potential at greater resolution in non-excitable cells."
slug: "project-1b"
showDate: false
showAuthor: false
showReadingTime: false
showEdit: false
---
{{< lead >}}
Last updated — May 2024
{{< /lead >}}

## Introduction

The key purpose of [Project 1B](https://www.aion.bio/research-roadmap/#project-1a) is to develop a voltage reporting protocol that is sensitive enough for usage with non-excitable cells and can be used during cell reprogramming. We will determine through this whether a voltage reporting dye or a genetically encoded voltage indicator is more suitable for our purposes. The goal is for a reporting technique with a less than 5mV margin for error and high temporal resolution. 

## GEVIs vs Dyes

| Benchmark                         | GEVIs                                         | Voltage-Sensitive Dyes                       |
|--------------------------------|----------------------------------------------|----------------------------------------------|
| **Sensitivity**                | High sensitivity to voltage changes          | Moderate to high sensitivity, varies by dye  |
| **Temporal Resolution**        | High temporal resolution                     | High, but can be limited by dye kinetics     |
| **Specificity**                | High, can be targeted to specific cell types | Lower, stains all cell membranes             |
| **Invasiveness**               | Non-invasive genetic encoding                | Invasive, requires dye loading               |
| **Phototoxicity**              | Lower phototoxicity                          | Can be phototoxic, especially under prolonged exposure |
| **Signal-to-Noise Ratio**      | High, due to specific expression             | Lower, due to background staining            |
| **Stability**                  | Stable expression in cells                   | Can be unstable, prone to photobleaching     |
| **Ease of Use**                | Requires genetic manipulation                | Easier to apply, just add dye                |
| **Multiplexing**               | Limited by available spectral variants       | More flexibility with different dyes         |
| **Cost**                       | Higher initial setup cost                    | Lower initial cost, but recurring expenses for dyes  |

At the time of writing this, rEstus[^1] is our leading GEVI candidate and Di-4-ANEPPS is our leading dye candidate. 

[^1]: Rühl P, Nair AG, Gawande N, Dehiwalage SNCW, Münster L, Schönherr R, Heinemann SH. An Ultrasensitive Genetically Encoded Voltage Indicator Uncovers the Electrical Activity of Non-Excitable Cells. Adv Sci (Weinh). 2024 Mar 25:e2307938. doi: 10.1002/advs.202307938. Epub ahead of print. PMID: 38526185.



