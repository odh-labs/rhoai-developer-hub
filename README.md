# Overview
Project to showcase a RHOAI experience enriched with RH Developer Hub 

# User Stories

1. As an AI Engineer I need access to an LLM so that I can develop my application
2. As an AI Engineer I need to develop a document processing pipeline that retrieve documents from multiple sources and prepare them for chunking.
3. ...

# Core Patterns

1. Document processing pipeline with Docling
2. RAG pattern
3. Llamastack pattern
4. MaaS pattern

# Features

TBC

# Suggested workflow

1. Select a template from Developer Hub. Examples:
   * Onboard into a new data science team (needs a default workbench created)
   * Build be a basic document processing pipeline
   * Deploy a model from the model catalogue and provide api connection details.
     * User has a basic python app that can test the LLM.
   * Create a new MCP server in llama stack
     * User gets a skeleton MCP server that they can continue to develop in VS Code and deploy to OpenShift
2. System clones a skeleton git repo with HELM chart
4. User enters details and creates a values file.
5. System creates a production git repo and Argo Application/Application Set
6. System applies the application to Argo.

# Implementation Plan

TBC
