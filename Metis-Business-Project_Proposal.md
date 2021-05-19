Metis Bootcamp - Business Module

Project Proposal

Emily Lorenzen

05/19/2021


# Precision clinical trials - identifying drugs that failed in clinical trials because of sensitivity to genetic variations

## Introduction
Clinical trials for novel therapeutics are costly and time-consuming. Despite promising result from preclinical research, the vast majority of potentially therapetuic compounds fail to pass clinical trials and become approved by the FDA. Typically, the reason for the failure of these compounds is either due to issues in safety or efficacy. Efficacy issues can arise due to genetic variations in the protein through which a drug acts. However, filtering of clinical trial patients by genetic information has just recently become viable due to technological advancements in genetic sequencing.

In this proposal, I will investigate the drugs that passed the first two phases of clinical trials (safety phases), but failed at either phase III or phase IV (efficacy phases). My goal is to identify drugs that failed due to sensitivity to genetic variations in the target protein. Candidate drugs may pass clinical trials if genetic information is evaluted prior to patient recruitment. Of note, these drugs have already passed the preclinical process, as well as phase I and phase II of clinical trials, greatly reducing the monetary cost for FDA-approval.

## Data
Data on clinical trials and results  will be obtained from the AACT database to obtain information on the drug, drug target, and phase of failure (https://aact.ctti-clinicaltrials.org/). Information on known genetic variants of proteins targeted by failed drugs will be obtained from human genomic variant (HGV) database (https://hgv.figshare.com/) and will include the following features - population frequency, variant type, coding or noncoding location, , mutation type, zygosity level, functional impact of variant, and whether the variant is located in the binding site or activation pathway. 

There are three approaches that can be used to validate therapeutic drug candidates to reevaluate in clinical trials that use genetic information to screen patients. (1) Molecular modeling to determine if variations in the target protein will affect drug affinity (2) benchmarking against a pharmacogenomic database (https://www.pharmgkb.org/) (3) in vitro, wet-lab research. 

A single unit of data will be a drug that failed in clinical trials with the features highlighted above. 

## Tools
My goal is to provide evidence of project feasibility to non-technical stakeholders. For this reason, I will use google sheets for exploratory data analysis. Tableau will be used for data visualization. 

SQL will be initially used to query data from AACT, HGV, and pharma

## Minimum Viable Project
First, I need to establish that there are drugs that failed clinical trials which target proteins with genetic variations. To further establish  will be to determine if the genetic variations in drug-targeted proteins must account for enoug certain percentage of the population 