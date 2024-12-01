# Data Directory Documentation

## Overview
This directory contains the eye-tracking and dialogue data collected from human-LLM programming interactions, supporting the analysis presented in "Mapping Cognitive Load in Human-LLM Programming Dialogues" (ACL 2024).

## Directory Structure
data/
├── processed/              # Processed and analyzed datasets
├── raw/                   # Raw eye-tracking and dialogue data
└── README.md             # This documentation file

## Dataset Description

### Primary Dataset Features
- **Total Interactions**: 444 programming dialogues
- **Participants**: University computing students (sophomore to PhD)
- **Experience Levels**: Novice (n=64), Intermediate (n=168), Advanced (n=192)
- **Collection Period**: [Collection Period]

### Data Categories

1. **Participant Information**
- Demographic data (age, gender, academic year)
- Programming experience (years, frequency)
- Academic background (major, confidence levels)

2. **Eye-Tracking Metrics**
- Fixation measurements (count, duration, patterns)
- Saccade metrics (count, amplitude, velocity)
- Dwell time statistics (duration, percentage)
- Areas of Interest (ChatGPT interface, code editor)

3. **Dialogue Content**
- Student prompts
- ChatGPT responses
- Interaction sequences
- Theme classifications

4. **Task Assessment**
- Difficulty ratings (with/without tools)
- Task completion metrics
- User confidence measures

## Data Format
- File format: CSV
- Encoding: UTF-8
- Timestamp format: milliseconds
- Missing values: encoded as null

## Key Variables

### Eye-Tracking Metrics
- `Fixation_count`: Number of fixations
- `Saccade_count`: Number of rapid eye movements
- `Dwell_time_gaze_ms`: Gaze duration in milliseconds
- `Duration_average_fixation`: Mean fixation duration

### Interaction Metrics
- `Student_prompt`: User input text
- `ChatGPT_answer`: LLM responses
- `AOI`: Area of Interest identifier (1 = ChatGPT, 0 = Code Editor)

### Experience Measures
- `YearsProgramming`: Programming experience (0.5 to 6 years)
- `ProgrammingFrequency`: Usage frequency (0 = Never to 5 = Daily)
- `ACYear`: Academic year (2-5)

## Data Processing Notes
1. Eye-tracking data collected using SmartEye AI-X (60 Hz)
2. Gaze calibration quality maintained at good (4) or excellent (5)
3. Invalid data points filtered based on DataValidity flag
4. Timestamps aligned across all measurements

## Usage Guidelines
- Please cite the accompanying paper when using this dataset
- Data is anonymized following IRB guidelines
- See primary paper for detailed analysis methodology

## Contact
[To be added after acceptance]
