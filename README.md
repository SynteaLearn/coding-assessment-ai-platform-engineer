# AI Platform Engineering Assessment

## Task
Build an AI assistant API for a corporate training platform.

## Requirements
- Employees ask questions about industry trends
- Assistant searches and provides answers
- Can fetch detailed content when users want to dive deeper
- REST API with terminal chat interface (Python or TypeScript)
- No frontend needed
- Use any LLM API

## Steps
0. Prepare mock search data (10 Google-like results)
1. Build the REST API
2. Create terminal chat interface for testing

## Example Mock Data
```json
{
  "query": "AI applications corporate training 2025",
  "results": [
    {
      "title": "How AI Is Shaping the Future of Corporate Training in 2025",
      "url": "https://trainingindustry.com/articles/ai-future-corporate-training",
      "snippet": "Explore how artificial intelligence is revolutionizing corporate learning with personalized training paths, real-time feedback, and adaptive learning systems..."
    }
    // ... 9 more results
  ]
}
```

## Example Interaction
```
User: "What's new in AI regulations?"
Assistant: [Provides summary from search results]

User: "Tell me more about that EU policy"
Assistant: [Fetches and discusses specific content]
```

## Deliverables
1. Working code with terminal chat
2. Brief document explaining your approach
3. Instructions to run it

## Time
4-6 hours (MVP quality expected)

## How to Submit
1. Fork this repo
2. Make your fork private
3. Add collaborator: [@feiwangai](https://github.com/feiwangai)
4. Work on your solution in your private fork
5. Email us when done

## What We Evaluate
- How you interpret requirements
- System design and architecture  
- Code quality
- How you handle search and content retrieval
- Documentation of your decisions

## Timeline
7 days to complete

Focus on building an MVP that works end-to-end.