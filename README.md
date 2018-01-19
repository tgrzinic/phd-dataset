# phd-dataset

Toni Grzinic, Hybrid method for malware Detection, PhD Thesis,
University of Zagreb, 2017.

This repository contains datasets used in my PhD thesis to build machine
learning models for static, dynamic and hybrid classifiers that are used to
detect new malware.

## Train01 dataset

Dataset Train01 contains stratified malware samples used to learn basic
classifiers S, D1 and D2 (static and dynamic models) that were later used  to 
build the final hybrid classifier. Malware samples are stratified from
a bigger dataset that contained malware samples collected from 2011 to 2016.
Malware samples were stratified using frequency distributions of their family
and type.

## Test01 dataset

Dataset Test01 contains malware samples that become available while writing
my PhD thesis (late 2016 and 2017). Samples from Test01 were used to test the
classification accuracy of the newly built hybrid classifier on an independent
dataset and for comparing its results with AV tools (Kaspersky, Avast).
