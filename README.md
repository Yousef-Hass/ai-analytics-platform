<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</head>
<body>

  <h1>AI-Driven Self-Service Analytics Platform</h1>
  <div class="subtitle">Technical Brief</div>

  <h2>Problem</h2>
  <p>
    Business teams needed fast and reliable access to insights without relying on data analysts or engineers.
    Existing workflows required manual SQL queries static dashboards and slow iteration cycles.
    The goal was to enable conversational analytics and deep dive analysis while maintaining performance reliability
    and data accuracy at scale.
  </p>

  <h2>Solution Overview</h2>
  <p>
    I helped design and build a backend heavy AI driven analytics platform that allowed business users to query
    data using natural language and receive both conversational explanations and visual insights.
    The system combined scalable Python services structured analytics pipelines and LLM powered reasoning layers.
  </p>
  <p>
    The platform was designed to support production usage with strict latency requirements and high query volume.
  </p>

  <h2>High Level Architecture</h2>
  <ul>
    <li>Backend services built in Python and FastAPI</li>
    <li>Modular microservices architecture separating data ingestion analytics and AI orchestration</li>
    <li>ETL pipelines for transforming raw operational data into analytics ready datasets</li>
    <li>LLM orchestration layer for query interpretation reasoning and response generation</li>
    <li>REST APIs consumed by a lightweight React interface</li>
    <li>Deployed on cloud infrastructure with containerization and CI pipelines</li>
  </ul>

  <h2>Data Flow</h2>
  <ul>
    <li>Raw data ingested from multiple sources into PostgreSQL and analytics stores</li>
    <li>ETL pipelines cleaned normalized and enriched data using Python and SQL</li>
    <li>User queries submitted via UI or API</li>
    <li>LLM layer translated natural language queries into structured analytics intents</li>
    <li>Backend services executed optimized SQL queries or analytical workflows</li>
    <li>Results passed back through the reasoning layer to generate explanations and summaries</li>
    <li>Final response returned as charts metrics and conversational output</li>
  </ul>

  <h2>Key Engineering Decisions</h2>
  <ul>
    <li>Backend first design to ensure scalability and consistency across UI and API clients</li>
    <li>Async processing for long running analytics queries to avoid blocking user requests</li>
    <li>Clear service boundaries between data processing AI reasoning and API layers</li>
    <li>SQL optimization and indexing to support low latency analytics queries</li>
    <li>Caching with Redis for frequently accessed insights and metadata</li>
  </ul>

  <h2>Performance and Reliability Improvements</h2>
  <ul>
    <li>Reduced average API response time by over 30 percent through query optimization and async workflows</li>
    <li>Improved system throughput by offloading heavy analytics jobs to background workers</li>
    <li>Increased platform stability during peak usage through better service isolation and monitoring</li>
    <li>Simplified deployments using Docker and CI pipelines which reduced release risk</li>
  </ul>

  <h2>Impact</h2>
  <ul>
    <li>Enabled non technical users to access insights without analyst involvement</li>
    <li>Shortened insight delivery from hours to seconds</li>
    <li>Improved trust in analytics by standardizing logic and explanations</li>
    <li>Created a reusable foundation for future AI agent workflows</li>
  </ul>

  <h2>Tech Stack</h2>
  <div class="tech-stack">
    Python FastAPI SQL PostgreSQL Redis React Docker AWS GCP OpenAI APIs LangChain
  </div>

</body>
</html>
