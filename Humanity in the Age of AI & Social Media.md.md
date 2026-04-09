# All in Your Toolbox: Boosting Efficiency for Local Government Leaders

## Interesting Projects across other municipalities
- Local LLM for PD
- Key word searching internal files, meeting minutes, agenda, videos, document drafting and benchmarking.
- Automation for building permits within a municipality
- Ways of funding these automations are tacking on technology fees for convenience
- School Speed Zone monitoring
- ArcGIS Indoors -> Asset mapping

### Internal LLM Training
*Note - This is not from the presentation, this was relevant research*

Instead of training a model, when using an open sourced model, retrieval augmented generation is the industry standard. You give the model a search engine.
- When you ask a question, the system searches internal documents for relevant text and "pastes" it into the prompt. It will then summarize that specific information.
  - This is best for data that changes frequently
- Low cost, no "training" required and you can see documents used by the AI.
- Best way of doing this would be llamaindex our drives with a SimpleDirectoryReader
  - You point it to your local network paths.
- You use a file watcher script, so when a file is saved or edited on the drive, the script automatically triggers re-indexing of that specific file.

## Using Prompts to Your Advantage
- To learn
- To research
- To streamline tasks
- To improve personal productivity

### Use the R-A-C-C-E method:
- Role
- Audience
- Context
- Constraints
- Examples

**With a .gov email you can get perplexity pro for free**
Click [here](https://www.perplexity.ai/pro) for more information.

**The AI Driven Leader**  is a book the lead speaker recommended. Click [here](https://www.amazon.com/AI-Driven-Leader-Harnessing-Smarter-Decisions/dp/B0DB8QL3ZK).