# Environment setup:
pip install python-dotenv langchain-mcp-adapters langgraph "langchain[openai]" mcp streamlit

# Run in separate terminals:
	Terminal 1 — Custom MCP Server
	
		python mcp_server.py

	Terminal 2 —  MCP Client 
	
		python mcp_client_langgraph.py
		
		or
		
		streamlit run streamlit_app.py