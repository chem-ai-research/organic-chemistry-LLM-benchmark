# Organic-chemistry-LLM-benchmark
Expert-curated organic chemistry benchmarks for evaluating large language model reasoning and scientific accuracy.
# ChemAIResearch — Organic Chemistry LLM Benchmark

**Expert-curated chemistry benchmarks for evaluating large language model (LLM) reasoning and scientific accuracy.**

## Overview

This project explores how large language models handle organic chemistry problems, with a focus on reaction prediction, mechanistic reasoning, stereochemistry, and common reasoning errors.

The goal is to develop structured, expert-reviewed evaluation datasets that assess not only whether a model predicts the correct product, but also whether its chemical reasoning is sound.

## Project Objectives

- Develop challenging organic chemistry evaluation problems.
- Establish reference answers and expert explanations.
- Identify common errors in predicted products, mechanisms, and stereochemical outcomes.
- Evaluate model responses using consistent review criteria.
- Organize findings into structured benchmark and error-analysis datasets.

## Benchmark Development

### Benchmark 1 — Reaction Prediction and Mechanistic Reasoning

The initial benchmark covers organic chemistry problems with structured fields for:

- Question and reaction conditions
- Expected product and mechanism
- Stereochemical outcome, where applicable
- Expert explanation and common traps
- References and review status

### Benchmark 2 — Advanced Chemistry Reasoning

The second benchmark focuses on problems designed to examine model reasoning, including cases where a response may contain partially correct reasoning but reach an incorrect chemical conclusion.

The evaluation framework considers:

- Product prediction accuracy
- Mechanistic correctness
- Stereochemical correctness
- Scientific reasoning quality
- Error classification and reviewer comments

## Evaluation Methodology

The intended workflow is:

1. Develop a chemistry problem.
2. Establish and verify the reference answer.
3. Collect model responses under documented conditions.
4. Assess the answer and reasoning against explicit criteria.
5. Classify errors and document reviewer findings.
6. Refine the benchmark through expert review.

## Preliminary Observations

Initial pilot testing has revealed cases in which multiple language models fail to predict the correct product for the same organic chemistry problem.

These observations motivate a more systematic investigation of chemistry-specific reasoning failures. Pilot results should not be interpreted as general performance rankings across models.

## About

ChemAIResearch is an independent project focused on expert-driven chemistry AI evaluation, benchmark development, and scientific reasoning assessment.

The project builds on expertise in organic chemistry, synthetic chemistry, and scientific research.

## Status

**In development.** Benchmark curation, evaluation criteria, and documentation are being refined. Reference answers and supporting sources require appropriate verification before external or commercial use.

## Contact

For research collaboration, chemistry benchmark development, or AI evaluation projects, please contact me through my GitHub profile.
