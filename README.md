# n8n Workflows Collection

A collection of advanced n8n workflows that leverage RAG (Retrieval-Augmented Generation), LLMs, and AI Agents for various automation tasks.

##🚀 Workflows Overview

###📚 Course RAG Workflow

File: PDFTextCourseRAGWorkflow/Course_RAG.json
A comprehensive RAG system for processing educational PDF documents and creating an intelligent Q&A system.

Features:

Downloads PDF files from Google Drive
Extracts and chunks text content
Generates contextual information for improved retrieval
Stores processed data in PostgreSQL and Google Sheets
Uses Pinecone vector database for semantic search
Chat interface with memory for course-related queries
Implements contextual retrieval for enhanced accuracy

Use Case: Transform course materials into an intelligent tutoring system

###🎯 PM Interview Simulator
File: PMIntterviewSimulatorWorkflow/PMInterview-RAG.json
An AI-powered Product Manager interview preparation system that conducts realistic mock interviews.

Features:

Processes YouTube PM interview transcripts
Categorizes questions by type, frameworks, and skills tested
Two-agent system: Interview Guide Generator + Interview Conductor
CV/Resume analysis and retrieval
Personalized interview questions based on candidate background
Stores interview patterns and candidate data in Pinecone
Real-time interview simulation with follow-up questions

Use Case: Prepare for PM interviews with personalized, realistic practice sessions

###💼 Job Hunter Agent

File: PMJobHunterWorkflow/Job Agent.json
An intelligent job search automation system that finds, analyzes, and applies to relevant positions.

Features:

Monitors RSS feeds for job postings
AI-powered job compatibility scoring
Automatic cover letter generation
Company name extraction
Duplicate job filtering
Google Sheets integration for job tracking
Resume-job matching analysis

Use Case: Automate job searching and application processes

###📺 YouTube Playlist RAG
File: PlaylistYouTubeRagWorkflow/YouTube-Contextual-RAG.json
A comprehensive system for processing multiple YouTube videos into a searchable knowledge base.

Features:

Processes multiple YouTube video transcripts
Extracts and cleans video descriptions
Creates timestamped content chunks
Generates contextual information for better retrieval
Stores in Google Sheets and Pinecone
Chat interface with video references and timestamps
Supports playlist-level content organization

Use Case: Create searchable knowledge bases from YouTube educational content

###🔍 Reddit Sentiment Analyzer
File: RedditSentimentAnalyserWorkflow/Reddit - Sentiment.json
An intelligent sentiment analysis system that monitors Reddit discussions about specific topics.

Features:

Searches Reddit for topic-specific posts
Filters high-quality posts by upvotes
AI-powered sentiment analysis and key point extraction
Aggregates opinions and generates summaries
WhatsApp notifications for insights
Tracks sentiment trends over time
Chat interface for topic analysis requests

Use Case: Monitor public opinion and sentiment about products, brands, or topics

###📹 Single YouTube RAG
File: SingleYouTubeRAGWorkflow/YouTube-Single-Contextual-RAG.json
A focused RAG system for processing individual YouTube videos with high accuracy.

Features:

Form-based video URL input
Single video transcript processing
Contextual chunk generation
Pinecone vector storage with video-specific namespaces
Chat interface with timestamp references
Processing status tracking
Optimized for individual video analysis

Use Case: Deep analysis and Q&A for specific YouTube educational videos

##🛠️ Technical Stack

Platform: n8n workflow automation
LLM: OpenAI GPT-4 models
Vector Database: Pinecone
Storage: Google Sheets, PostgreSQL
AI Features: Embeddings, Reranking (Cohere), Contextual Retrieval
Integrations: YouTube, Reddit, Google Drive, WhatsApp

##📋 Prerequisites

n8n instance (cloud or self-hosted)
OpenAI API key
Pinecone account and API key
Google Sheets API access
Various service credentials (Reddit, YouTube, etc.)

🚀 Getting Started

Import the desired workflow JSON file into your n8n instance
Configure the required credentials for each service
Set up the necessary databases and storage systems
Test the workflow with sample data
Activate and start using!


These workflows demonstrate advanced AI automation patterns combining retrieval-augmented generation, multi-agent systems, and intelligent data processing.
