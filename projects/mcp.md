---
layout: project
type: project
image: img/51DBd7O6GEL.jpg
title: "AI-Powered Project Knowledge Manager (Gemini Observatory)"
date: 2025
published: true
labels:
  - Python
  - FastAPI
  - Model Context Protocol
  - LLM Agents
  - PostgreSQL
  - Elasticsearch
summary: "An AI-powered internal knowledge and project management system built for the Gemini Observatory, leveraging Model Context Protocol servers and LLM agents to unify and query technical data across multiple platforms."
---

<img class="img-fluid" src="../img/gemini/gemini-header.png">

This project is a full-stack, AI-powered project knowledge manager developed during my Software Engineering Internship at **NOIRLab’s Gemini Observatory**. The goal was to reduce friction in how technical staff retrieve information across fragmented tools by providing a single, intelligent interface backed by LLM agents and a custom Model Context Protocol (MCP) server.

The application enables users to query, summarize, and interact with project data spanning operational logs, documentation, and issue tracking systems using natural language.

<hr>

### Project Overview

Gemini Observatory engineers and researchers rely on multiple platforms—such as Elasticsearch logs, Google Workspace, and Atlassian Jira/Confluence—to manage projects and operations. Retrieving context across these systems was time-consuming and required deep platform-specific knowledge.

I designed and implemented a system that uses **LLM agents** and a **custom MCP server** to unify these data sources into a single conversational and dashboard-driven interface, enabling faster decision-making and improved collaboration.

<hr>

### Architecture and Key Components

At the core of the system is a **custom Model Context Protocol server** written in Python. The MCP server exposes structured tools that allow LLM agents to safely and consistently interact with Gemini Observatory data sources, including:

- Elasticsearch log data for operational insights  
- Google Workspace (Docs, Drive, Calendar) for project artifacts  
- Atlassian Jira and Confluence for issue tracking and documentation  

A **FastAPI-based REST backend** handles OAuth 2.0 authentication, request routing, and communication between the frontend, LLM agents, and MCP tools. Credentials and tokens are securely stored in a **PostgreSQL database** using SQLAlchemy ORM.

LLM agents are responsible for orchestrating tool usage, synthesizing responses, and automating project management tasks such as summarization, cross-system lookup, and status reporting.

The frontend is a responsive web application built with **HTML, CSS, and JavaScript**, featuring a dashboard view and a chat-based interface that allows users to seamlessly interact with project data using natural language.

<hr>

### Impact

This system significantly reduced the time required for Gemini Observatory technical staff to locate and contextualize project information. By abstracting away platform-specific complexity and exposing a unified, intelligent interface, the application improved internal workflows and lowered the cognitive overhead of managing large-scale scientific projects.

<hr>

### Presentation and Communication

As part of a professional development program, I authored a formal project abstract, created a Google Slides presentation, and presented this work at an internal symposium. I was later selected to present the project at the **National Science Foundation’s “The Solar System in Context” conference**, where I communicated both the technical design and real-world impact to technical and non-technical audiences.

<hr>

Source: <em>Internal NOIRLab / Gemini Observatory project (not publicly available)</em>
