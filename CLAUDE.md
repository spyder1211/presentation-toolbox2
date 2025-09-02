# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains materials for a **Municipal Staff AI Workshop** focused on demonstrating practical AI applications for local government operations. The project includes presentation materials, Dify chatbot implementation, and comprehensive documentation for 4 AI demonstration scenarios.

## Repository Structure

### Core Components

- **`index.html`** - Main HTML presentation (20 slides) showcasing 4 AI demonstrations
- **`requirement.md`** - Detailed specifications for workshop demonstrations and technical requirements
- **`dify/`** - Complete Dify chatbot implementation for Tsuru City with structured knowledge base
- **`pdf/`** - Reference documents including government AI guidelines
- **`image-*.png`** - Demo screenshots and visual examples for presentations

### Dify Integration Architecture

The `/dify/docs/` directory contains a fully implemented RAG chatbot system:

- **Knowledge Base Structure**: Prioritized content organization (01_極めて高優先度, 02_高優先度, 03_中優先度)
- **Phase-based Development**: Documented in `phase*_作業ログ.md` files showing iterative implementation
- **Production-Ready Configuration**: Complete Dify setup guide and metadata for deployment

## Workshop Demonstrations

The presentation covers 4 practical AI applications:

1. **Image Generation** - Using ChatGPT/DALL-E 3 for promotional content creation
2. **DeepResearch** - Automated research and report generation for municipal AI case studies  
3. **Document Creation** - AI-assisted policy guideline development using government templates
4. **RAG Chatbot** - Tsuru City-specific knowledge base with real municipal data

## Development Workflow

### Presentation Updates
- Edit `index.html` for slide content modifications
- Update `requirement.md` for specification changes
- Ensure image references match actual file names in root directory

### Dify Chatbot Maintenance
- Knowledge base updates should follow the priority structure in `/dify/docs/knowledge_data/`
- Reference `Dify_ナレッジベース設定ガイド.md` for deployment procedures
- Test with sample questions from `テスト用サンプル質問集.md`

### Content Consistency
- All demonstration content should reflect real municipal use cases (Tsuru City examples)
- Maintain alignment between `requirement.md` specifications and `index.html` implementation
- Update phase logs when making significant changes to Dify components

## Key Implementation Details

The Dify chatbot implementation includes:
- **18 structured knowledge files** covering municipal services
- **3-tier priority system** for content organization
- **Production deployment configuration** with specific chunking and retrieval parameters
- **Comprehensive test scenarios** for municipal Q&A validation

This project demonstrates enterprise-level AI implementation for local government, with particular attention to data privacy, accuracy, and practical municipal applications.