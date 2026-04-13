# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Miscellaneous public code snippets and utilities. Currently contains a single Boto3 script that ensures every VPC in an AWS account has an S3 gateway endpoint with all route tables attached.

## Setup

python3 -m venv .venv && source .venv/bin/activate
pip install boto3

## Common Commands

# Run the S3 gateway endpoint script
python s3_gateway_endpoint.py
