# AI Gateway Stress Testing Tools

A collection of TypeScript scripts for stress testing AI gateway endpoints that handle LLM (Large Language Model) and image generation requests.

## Overview

This repository contains three stress testing scripts:
- `dualStressTest.ts`: Test two different gateways simultaneously for both LLM and image generation
- `stressTest.ts`: Test LLM gateway endpoints
- `imageStressTest.ts`: Test image generation gateway endpoints

## Features

- Concurrent request handling
- Configurable number of requests
- Automatic retry mechanism
- Detailed logging and statistics
- Support for both LLM and image generation endpoints
- Ability to test multiple gateways simultaneously
- Comprehensive performance metrics and summaries

## Prerequisites

- Node.js (v14 or higher)
- TypeScript
- `axios` for HTTP requests
- Environment variables properly configured

## Installation

1. Clone the repository:
