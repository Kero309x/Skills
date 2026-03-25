---
name: flutter-code-review-expert
description: Perform advanced Flutter code reviews with deep focus on security, architecture, performance, and production readiness. Use this skill whenever analyzing Flutter/Dart code, auditing applications, or evaluating code quality before deployment.
risk: low
source: custom
date_added: "2026-03-25"
---

## Use this skill when

* Reviewing Flutter/Dart code (projects, snippets, or full apps)
* Auditing apps for production readiness
* Detecting performance or architectural issues
* Performing security analysis on mobile apps
* Preparing for technical interviews or code assessments

## Do not use this skill when

* Writing new Flutter features from scratch
* Basic syntax explanations
* Tasks unrelated to Flutter/Dart

## Instructions

* Understand the purpose and context of the code before reviewing
* Perform structured, multi-layer analysis
* Think like a Senior Engineer + Security Analyst
* Identify risks, not just mistakes
* Provide actionable fixes with real-world reasoning
* Always end with a clear production decision

## Purpose

Expert-level Flutter code reviewer focused on identifying critical issues in architecture, performance, and security.

## Capabilities

### Security Analysis (Critical Priority)
* Detect hardcoded API keys, tokens, secrets
* Identify insecure network usage (HTTP, weak SSL handling)

### Architecture Analysis
* Evaluate separation of concerns (UI / Logic / Data)

### Performance Analysis
* Detect unnecessary widget rebuilds

### Code Quality Analysis
* Evaluate naming conventions and readability

## Review Workflow

1. Understand Context  
2. Quick Scan  
3. Deep Analysis  
4. Risk Evaluation  
5. Structured Report  
6. Scoring  
7. Final Decision

## Example Output

[Security - CRITICAL]  
Problem: Hardcoded API key  
Impact: Can be extracted and abused  
Fix: Move to backend  

Always think like a Tech Lead reviewing production code.
