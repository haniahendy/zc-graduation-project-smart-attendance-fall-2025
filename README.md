# Graduation Project: Smart Attendance System Using Face Recognition

Zewail City of Science and Technology - Computer Science Department, School of Computing
Graduation Project Final Report, Fall Semester 2025

## Team 32
- Hania Khaled (DSAI)
- Farah Samir (DSAI)
- Yassmin Raafat (Software Development)
- Hager Ali (DSAI)

Supervisor: Dr. Mohamed Ghalwash

## Overview
An automated classroom attendance system that captures a single classroom image every minute instead of processing continuous video, detects and recognizes student faces, and computes attendance from the total duration each student appears across frames. The design combines:
- Two-stage face detection with a Haar Cascade fallback
- CNN (ResNet architecture) face recognition over facial embeddings
- A centralized database for attendance records
- A web-based dashboard for instructors to monitor attendance statistics in real time

## Work completed in Fall 2025 (per the report)
- Hania Khaled (DSAI): data collection and preparation - captured full student images, performed face cropping using Haar Cascade detection, and built the dataset used for model training.
- Farah Samir (DSAI): trained and fine-tuned the face recognition model on a pre-trained ResNet; evaluated and validated model accuracy.
- Hager Ali (DSAI): dataset labeling, preprocessing validation, documentation; supported model evaluation and testing.
- Yassmin Raafat (SWD): system architecture design, UI/dashboard prototype, backend/database/API integration concepts; planning and coordination.
- A preliminary web dashboard prototype was designed and a shared project repository was set up.

## Planned for Spring 2026 (per the report; not covered here)
System implementation, end-to-end integration, and testing/validation phases, with individual responsibilities: Hania - face detection pipeline, recognition model training, system integration; Farah - preprocessing, model training/evaluation, attendance processing logic; Hager - dataset labeling, model optimization, testing; Yassmin - UI, backend-frontend integration, database, deployment.

## Contents
- `Smart-Attendance-System-Final-Report.pdf` - the team's Fall 2025 final report (19 pages). Student IDs and personal data removed for publication.

## Project status
This repository holds the Fall 2025 report only. It covers requirements, design and fall-semester progress. Per the report, implementation, integration and testing were planned for Spring 2026. This repository does not document that implementation.

## Notes
- This repository contains the Fall 2025 project report only. Implementation code is not included here; the report's appendix references the team's shared repository under a teammate's account.
- Full individual team-member names are retained for attribution; student IDs were removed.
