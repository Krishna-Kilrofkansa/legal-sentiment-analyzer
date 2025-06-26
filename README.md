#AI Legal Sentiment Analyzer#

A few-shot sentiment analysis tool for legal documents built on IBM watsonx.ai. This repository contains code to automate sentiment classification (positive/negative/neutral) of legal text using FLAN-T5 models via IBM Watson Machine Learning.

Project Overview

The AI Legal Sentiment Analyzer leverages IBM watsonx.ai foundation models to classify legal text sentiment into positive, negative, or neutral categories. It accelerates the review of case summaries, client feedback, and contracts for law firms and compliance teams by:

Automating sentiment tagging via few-shot prompting

Summarizing insights for large text corpora

Reducing manual review time and increasing consistency

Few-Shot Classification — uses minimal examples per class (positive/negative/neutral) for efficient model prompting.

IBM watsonx.ai Integration — runs FLAN-T5 (or alternate) models on IBM Cloud with minimal setup.

Data Loading from Cloud Object Storage — fetches CSV files directly from IBM COS buckets.

Customizable Prompts — easily adapt instruction templates and example placeholders.
